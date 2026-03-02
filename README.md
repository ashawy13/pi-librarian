# 🚀 pi-librarian - Your GitHub Assistant for Easy Management

[![Download pi-librarian](https://img.shields.io/badge/Download-pi--librarian-FF5733?style=for-the-badge&logo=github)](https://github.com/ashawy13/pi-librarian)

## 📥 Overview

**pi-librarian** is a tool designed to help you manage your GitHub projects more efficiently. This extension allows you to use various tools specifically for analyzing GitHub repositories without needing programming skills.

## 🌟 Features

- **`librarian` Tool**: A GitHub-focused subagent for effective repository management.
- **Supporting Repository Analysis Tools**:
  - `read_github`: Easy access to repository content.
  - `search_github`: Quickly find information within repositories.
  - `commit_search`: Review past changes and commits with ease.
  - `diff`: Compare versions of files.
  - `list_directory_github`: View directory structures in repositories.
  - `list_repositories`: Easily view all repositories linked to your account.
  - `glob_github`: Efficiently collect data through patterns.

## ⚙️ How It Works

The `librarian` tool runs an isolated `pi` subprocess specifically configured for GitHub tasks. It executes commands with the following settings: `--mode json --no-session`. This setup ensures that you get straightforward answers in JSON format, making it easier to understand the outputs.

## 🛠️ Requirements

Before you can use **pi-librarian**, make sure you have the following:

- **GitHub CLI** (`gh`) installed. You can download it from [GitHub CLI Releases](https://github.com/cli/cli/releases).
- An authenticated GitHub session. You can establish this by running the following command in your terminal:

```bash
gh auth login
```

## 📂 Location

This extension is auto-discovered in your project. You can find it at:

- `.pi/extensions/pi-librarian/index.ts`

After making edits, use the command `/reload` in your `pi` application to load the extension.

## ⚠️ Notes

- This version currently supports only GitHub. There is no compatibility for Bitbucket Enterprise paths at this time.
- The output from these tools is in JSON format, allowing for reliable parsing and usage.

## 📦 Download and Install

To get started with **pi-librarian**, visit this page to download:

[Download pi-librarian](https://github.com/ashawy13/pi-librarian)

Follow the installation instructions above to ensure everything is set up correctly.

## 📝 Usage

Once you have everything installed, using **pi-librarian** is straightforward. Simply invoke the `librarian` tool through your terminal or application interface and start working with your GitHub repositories. For example, running the `read_github` command will give you access to your project's content instantly.

Utilize the various supporting tools based on your need:

- For retrieving content and details, use `read_github`.
- To find specific items, employ `search_github`.
- For understanding project changes, consider using `commit_search` or `diff`.

## 🔗 Additional Resources

For further reading and advanced configurations, refer to the official GitHub documentation. You can find extensive resources and examples for using `gh` effectively.

Maintain your productivity by leveraging these tools to automate repetitive tasks. This will save you time and let you focus on what matters most in your projects.