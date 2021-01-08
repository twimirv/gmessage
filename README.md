# gMessage

This is a script to send Google Chat messages using incoming webhooks.

## Installation:

### Automated install:
1. Clone repository
2. In repository root, run ```bin/gmessage-install```
3. Done.

### Manual install:
1. Clone repository
2. Copy gmessage into ```/usr/local/bin/``` (note: may require sudo)
3. If you have earlier version installed, please remove ```gmessage.sh``` from ```/usr/local/bin/``` for it's no longer needed.

## Usage:
1. Open terminal, type gmessage and press enter.
2. Set up chatroom by using built in tool.
3. To send messages, use gmessage with parameters. The first parameter is chatroom nickname, the second parameter is the message you want to send surrounded by single quotes.

Example of usage:
```gmessage myAwesomeChat 'Hello World'```
