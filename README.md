# A Bun template on Gitpod

This is a [Bun](https://bun.sh/) template generator configured for ephemeral cloud development environments on [Gitpod](https://www.gitpod.io/).

## Next Steps

Click the button below to start a new development environment:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Emnolope/gitpod-template-bun-next-js)

## Under the Hood


The Bun generator cries when the directory isn't empty.

When the Gitpod environment initializes, the `.gitpod.yml` configuration:

1. Checks if a `package.json` file exists in the current directory.
2. If it doesn't, it temporarily moves all contents of the directory to a temporary location.
3. It then sets up a new Next.js project in the current directory using Bun.
4. After the Next.js project setup, the original contents of the directory are moved back from the temporary location.

## Get Started With Your Own Project

### A new project

Click the above "Open in Gitpod" button to start a new workspace. Once you're ready to push your first code changes, Gitpod will guide you to fork this project so you own it.

### An existing project

Copy and commit the [`.gitpod.yml`](./.gitpod.yml) to your existing project to have the same configuration of this template. For a comprehensive guide, please see the [Getting Started](https://www.gitpod.io/docs/getting-started) documentation.
