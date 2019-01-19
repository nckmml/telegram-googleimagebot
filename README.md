# Telegram Google Image Bot

## How to make it work
Contact BotFather on Telegram (https://telegram.me/botfather) via private message and write the '/newbot' command. BotFather will ask you for a name (anything) and a username (globally unique). In return you will get an API token, looking like this:

```
110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw
```

This token is used to authenticate requests to the bot API.

### Insert your API key and Custom Search ID
edit the api.py and copy your API key and Custom Search ID into the variables on top and build the container or start it without docker

### Build docker image by yourself
Handy instructions are in the Makefile.

```
make build
TOKEN=110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw make run
```

### Without docker

start the bot.py with your Token:

```
$ bot.py 110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw
```

### Usage

Add the bot to a telegram group or write a message to him with

```
/img query
```
