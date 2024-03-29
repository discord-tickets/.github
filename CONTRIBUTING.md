# Contributing

Thank you for considering making a contribution to Discord Tickets.

Before contributing, please read the [code of conduct](CODE_OF_CONDUCT.md), which all contributors must follow.

You can add yourself to [CONTRIBUTORS.md](https://github.com/discord-tickets/bot/blob/main/CONTRIBUTORS.md) using the [all-contributors bot](https://allcontributors.org/docs/en/bot/usage).

You don't need to write code to contribute; all contributions are welcome and encouraged. You could:

- [Submit a bug report](#submitting-a-bug-report) issue
- Help with bug triage
- [Request a new feature (or an improvement to an existing feature)](#submitting-a-feature-request)
- [Improve documentation](#updating-documentation) (the [website](https://discordtickets.app), or JSDoc comments)
- [Help translate](#translating)
- Create a tutorial (a video or page on the docs)
- [Answer someone's question in Discussions](https://github.com/discord-tickets/bot/discussions/categories/support-q-a?discussions_q=category%3A%22Support+%28Q%26A%29%22+is%3Aunanswered)
- Respond to an issue or pull request

If you want to contribute but don't know how, and this file doesn't answer your questions, [start a discussion](https://github.com/discord-tickets/bot/discussions/new) or [join the Discord support & community server](https://go.eartharoid.me/discord) to ask for guidance.

**Issues are for:**

- Bug reports
- Requesting changes to existing features

Please label your issues appropriately.

**Discussions are for:**

- Support (also on [Discord](https://go.eartharoid.me/discord))
- General questions (also on [Discord](https://go.eartharoid.me/discord))
<!-- - Requesting new features -->

Please read ["Welcome to Discord Tickets Discussions!"](https://github.com/discord-tickets/bot/discussions/77) before starting a discussion!

## Submitting a bug report

Issues should be used to report bugs. If you have found a bug, check to see if it has already been reported or resolved. If it hasn't, you can [create a new issue](https://github.com/discord-tickets/bot/issues/new/choose) using the "Bug report" template. Please include as much information as possible in your report.

## Submitting a feature request

<!-- To request a new feature, [start a new discussion](https://github.com/discord-tickets/bot/discussions/new?category=Ideas) under the Ideas category so other members of the community can discuss the request and vote on it. -->

To request a new feature for the bot, login to [Feedbacky](https://app.feedbacky.net/b/dsctickets) and submit an idea.

If you would like to request changes to an existing feature, it may be better to [create an issue](https://github.com/discord-tickets/bot/issues/new) instead (use the `enhancement` label).

## Creating a pull request

To edit the documentation, translate, or contribute code to this project, you will need to [create a new pull request](https://github.com/discord-tickets/bot/compare). For large changes, you should **consider creating an issue** (or commenting on an existing one) first, as it could save you some time.

You should name your commits using [**this commit message format**](https://github.com/angular/material/blob/master/.github/CONTRIBUTING.md#-commit-message-format).

### Contributing code

Any code changes should be accompanied by any necessary documentation changes.

**You should install the ESLint extension in your editor** to help you follow the code style.

- Use single quotes
- Indentation should use tabs not spaces
- Classes should be named in PascalCase
- Functions should be named in camelCase
- Variables and constants should be named in camelCase
- Use the latest JS features (destructuring, arrow functions etc)
- Use the British spelling (colour not color), except where it sucks (center not centre)

### Translating

If you want to change the meaning of messages, please customise your own locale files.

**Please review the [translation instructions](https://hosted.weblate.org/projects/discord-tickets/#information) before you begin.**

To get started, login to [Weblate](https://hosted.weblate.org/engage/discord-tickets/) with your GitHub account.

### Updating documentation

#### Website

The documentation is written in Markdown, with extensions for additional features. See the [Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/abbreviations/) for details.

**Please install a Markdown linting extension in your editor.**

If you would like to see a live preview of your changes you can install MkDocs locally after cloning the repository (requires python).

1. Install with `pip install -r requirements.txt`
2. Run `mkdocs serve`

#### JSDoc

Feel free to improve or add JSDoc comments in the JavaScript files.
