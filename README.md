# helth-bot

## Contributing to helth-bot

1. Fork the Repo
1. Clone repo in your local workspace `git clone <repo_url>`  
1. Track origin/dev branch `git branch dev`
1. Create new feature branch `git checkout -b new-feature-branch`
1. Commit your change `git commit -m "message"` 
1. Push your change `git push origin new-feature-branch`
1. Create Pull Request using UI

Reference: https://www.youtube.com/watch?v=8lGpZkjnkt4&ab_channel=Fireship

## Setting up env

To use the [Telegram Bot API](https://core.telegram.org/bots/api), 
you first have to [get a bot account](https://core.telegram.org/bots) 
by [chatting with BotFather](https://core.telegram.org/bots#6-botfather).

BotFather will give you a *token*, something like `123456789:AbCdfGhIJKlmNoQQRsTUVwxyZ`.

Put it in a file named `.env`:

```
BOT_TOKEN=123456789:AbCdfGhIJKlmNoQQRsTUVwxyZ
```

## Installing required modules

```
yarn install
```

## Running bot server locally

```
yarn start
```

## Linting js source files

```
yarn lint
```
...and fix (some of the) lint errors

```
yarn lint-fix
```