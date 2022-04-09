# learn-javascript-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that An automated bot that guide you through on learning JavaScript programming language.

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t learn-javascript-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> learn-javascript-bot
```

## Contributing

If you have suggestions for how learn-javascript-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 yapyeeqiang <yapyeeqiang@gmail.com>
