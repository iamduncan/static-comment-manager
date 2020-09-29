# static-comment-manager

> A GitHub App built with [Probot](https://github.com/probot/probot) that A
> github app for managing comments on a static website

## Functionality overview

1. When a user submits a comment it can be sent async to the bot.
2. The bot creates a new pull request with a new file containing the comment
   content.
3. When the pull request is merged, the comment will be available to the static
   site builder.

## Setup

```sh
# Install dependencies
npm install

# Compile
npm run build

# Run
npm run start
```

## Contributing

If you have suggestions for how static-comment-manager could be improved, or
want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2020 Duncan Brown <iamduncanbrown@gmail.com>
