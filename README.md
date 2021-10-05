# devto-github-template

[![Build Status](https://github.com/sinedied/devto-github-template/workflows/publish/badge.svg)](https://github.com/sinedied/devto-github-template/actions)

> Example repository setup for synchronizing markdown files as dev.to articles, using assets hosted on GitHub.

## Getting started

1. Select **Use this template** on GitHub. This will create a new repository on your account from this template.

2. Go to https://developers.forem.com/api/#section/Authentication/api_key and follow the **Getting an API key** instructions to generate your own dev.to API key.

3. Select the **Settings** tab on your GitHub repository, then go to the **Secrets** section.

4. Add a secret called **DEVTO_TOKEN** with the value of your dev.to API key.

Now your articles are ready to be published on dev.to! 🎉

Have a look a the example article in `posts/example.md` to see how it works, then you just have to commit and push your changes to have them reflected on dev.to.

## How it works

This template is based on the [publish-devto](https://github.com/sinedied/publish-devto) action, which uses under the hood the [devto-cli](https://github.com/sinedied/devto-cli) to publish your articles.

You can find more information about how it works in the [CLI readme](https://github.com/sinedied/devto-cli).
