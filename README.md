# Notify.vim
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/fntlnz/notify.vim?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Rationale
This plugin is intended to be used by with other plugins that do background jobs and wants to notify the user about the success of a specific job.

## Supported operating systems
Right now we have implemented only the default Mac OS X notification system via osascript and the Ubuntu notify-send.

## Usage
To send a notification

```vim
call Notify('Title', 'Body')
```
