---
title: Dev Containers
weight: 45
description: What a dev container is, and how to add one to a repository.
last_reviewed_on: 2026-06-18
review_in: 6 months
---

# Dev Containers

When you open a Codespace, GitHub needs to know which tools to install. It reads that from a dev container: a configuration file named `.devcontainer/devcontainer.json` stored in the repository.

If a repository has one, everyone who opens a Codespace there gets the same setup automatically. If it does not, GitHub falls back to a general-purpose environment that works for most common languages.

## What this means for you

As someone using Codespaces, you usually do not need to do anything. The repository maintainers set up the dev container, and GitHub applies it when your Codespace starts.

If you maintain a repository, adding a dev container means contributors get an identical environment without setting anything up by hand. That avoids a lot of "it only works on my machine" support.

## Adding a dev container

1. Create a `.devcontainer` folder in your repository.
2. Add a `devcontainer.json` file inside it.
3. Pick a base image from GitHub's [pre-built images](https://github.com/devcontainers/images).
4. List any extra tools, extensions, or setup commands your project needs.

A small example for a Python project:

```json
{
  "name": "My Python Project",
  "image": "mcr.microsoft.com/devcontainers/python:3.12",
  "customizations": {
    "vscode": {
      "extensions": ["ms-python.python", "ms-python.black-formatter"]
    }
  }
}
```

You can test the same configuration locally with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) before you commit it, which is handy for checking it works.

## Related links

- [Introduction to dev containers](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers)
- [Dev container templates](https://containers.dev/templates)
- [devcontainer.json reference](https://containers.dev/implementors/json_reference/)
