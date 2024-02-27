## Telegram Bot. Guess Pokemon. Example

Writtent in [Мавка](https://xn--80aaf6ah.xn--j1amh/)

## System Requirements
- Node 21
- NPM

## Recommended IDE
- VS Code

## Installation

### Dependencies
```
npm install
```

### Environment Variables
Bot needs configuration file, which contains Telegram token and URL to Telegram Bot API to run.
Token can be obtained via [BotFather](https://t.me/botfather).

[More here](https://core.telegram.org/bots/features#creating-a-new-bot)

Next, one has to create file `_конфігурація.м` with next content.

```
;; Here you have to put token provided by [BotFather](https://t.me/botfather)
токен = "7052***228:AAGxjwFrqn5807Ut****JePZ1lC3R9bGkCc"

;; If you want be able to connect with this URL — ask me
урл_адреса = "https://api.telegram.org"

дати токен
дати урл_адреса
```

## Run
```
npm run start
```