---
title: Everyday Tasks
weight: 35
description: Stopping, deleting, and personalising Codespaces, and forwarding ports.
last_reviewed_on: 2026-06-18
review_in: 6 months
---

# Everyday Tasks

Once you are working in a Codespace, these are the tasks you will use most often.

## Stopping a Codespace

A Codespace stops on its own after 30 minutes of inactivity. You can also stop it yourself, which is worth doing whenever you finish for the day.

- On [github.com/codespaces](https://github.com/codespaces), open the `...` menu next to the Codespace and select Stop codespace.
- In VS Code, open the Command Palette and run Codespaces: Stop Current Codespace.

Stopping keeps your files exactly as they were and pauses the compute cost.

## Deleting a Codespace

When your work is pushed and you no longer need the environment, delete it. A stopped Codespace still uses storage until you do.

Go to [github.com/codespaces](https://github.com/codespaces), open the `...` menu, and select Delete.

Deleting cannot be undone, so push anything you want to keep first.

## Forwarding a port

If you run a local server inside a Codespace, for example a web app on port 3000, GitHub can give you a URL to open it in your browser. Detected ports show up in the Ports panel at the bottom of the editor, and you can add one manually if it is not picked up. Forwarded ports stay private to you unless you change their visibility.

See [forwarding ports in your codespace](https://docs.github.com/en/codespaces/developing-in-a-codespace/forwarding-ports-in-your-codespace) for the details.

## Personalising your setup

You can carry your own shell configuration and editor settings into every Codespace using a [dotfiles repository](https://docs.github.com/en/codespaces/setting-your-user-preferences/personalizing-github-codespaces-for-your-account#dotfiles). GitHub applies them automatically each time you create a Codespace.

## Rebuilding a Codespace

If your environment stops behaving, for example after a tool update, you can rebuild it. A rebuild resets the container but keeps your source files and saved work. From the Command Palette, run Codespaces: Rebuild Container.

## Related links

- [Manage your Codespaces](https://github.com/codespaces)
- [Using source control in a Codespace](https://docs.github.com/en/codespaces/developing-in-a-codespace/using-source-control-in-your-codespace)
- [Personalising with dotfiles](https://docs.github.com/en/codespaces/setting-your-user-preferences/personalizing-github-codespaces-for-your-account#dotfiles)
