# renovate-config

[![license](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/praha-inc/renovate-config/blob/main/LICENSE)
[![Github](https://img.shields.io/github/followers/praha-inc?label=Follow&logo=github&style=social)](https://github.com/orgs/praha-inc/followers)

This is a Renovate config commonly inherited by PrAha products.

Use this setting to keep up with updates to the library and maintain high code quality.

## 👏 Getting Started

### 1. Install Renovate App

Install the [Renovate App](https://github.com/apps/renovate) in the repository.

### 2. Allow auto merge

Allow [automatic merging](https://docs.github.com/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/automatically-merging-a-pull-request) of repositories to make Renovate auto-merge work.

Updates below the minor version will be merged automatically, so be sure to use [branch protection rules](https://docs.github.com/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule) accordingly.

### 3. Install Auto Approve Bot

Install the [Approve App](https://github.com/apps/renovate-approve) that automatically approves pull requests in the repository.

If merging a pull request requires the approval of two people, install an additional [Approve2 App](https://github.com/apps/renovate-approve-2) in the repository.

### 4. Configure Renovate

Create a Renovate configuration file (`renovate.json`), and add `github>praha-inc/renovate-config` to the extends property.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>praha-inc/renovate-config"
  ]
}
```

If additional settings are required, modify the configuration accordingly.

Check the [Renovate documentation](https://docs.renovatebot.com/configuration-options/) for configuration details.

## 🤝 Contributing

Contributions, issues and feature requests are welcome.

Feel free to check [issues page](https://github.com/praha-inc/renovate-config/issues) if you want to contribute.

## 📝 License

Copyright © 2024 [PrAha](https://www.praha-inc.com/).

This project is [```MIT```](https://github.com/praha-inc/renovate-config/blob/main/LICENSE) licensed.
