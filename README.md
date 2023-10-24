# ChatGPT integration with Jira

This project contains a Forge app written in JavaScript that connects to Azure ChatGPT instance to provide useful internal comments when a new issue is created.

For more information, please see the [document](https://docs.google.com/document/d/1FESPEJdeH53Vir_IRxBnY5DnD8k7Nrd8OaOEEYSMVhc/edit?usp=sharing) about how to deploy Forge Apps.

## Requirements

See [Set up Forge](https://developer.atlassian.com/platform/forge/set-up-forge/) for instructions to get set up.

## Quick start
- Install top-level dependencies:
```
npm install
```

- Deploy your app by running:
```
forge deploy
```

- Install your app in an Atlassian site by running:
```
forge install
```

### Notes
- Use the `forge deploy` command when you want to persist code changes.
- Use the `forge install` command when you want to install the app on a new site.
- Once the app is installed on a site, the site picks up the new app changes you deploy without needing to rerun the install command.
