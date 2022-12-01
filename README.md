# omnifocus-plugin-open-jira-ticket
Open Jira ticket for the selected task or project.

## Quick Start Guide

### Dependencies

This plugin depends on the [omnifocus-plugin-libdev](https://github.com/xbot/omnifocus-plugin-libdev) library.

### Installation

Clone the repo and link it in the Automation Configuration dialog in OmniFocus, or add it as a git submodule to the default plugin folder of OmniFocus. I recommend the latter for an easier synchronization with other devices.

```shell
cd ~/Library/Mobile Documents/iCloud~com~omnigroup~OmniFocus/Documents/Plug-Ins

git init

# Install the dependent library, ignore this if you have already installed it.
git submodule add https://github.com/xbot/omnifocus-plugin-libdev.git libdev

git submodule add https://github.com/xbot/omnifocus-plugin-open-jira-ticket.git open-jira-ticket

# For updating:
git submodule update --remote --recursive
```

### Configuration

The project name must begin with a form like 'DEV-XXXX'.

First of all, Jira URL must be set before using this plugin.

In macOS, hold the CTRL key and click the menu item `Automation` → `Open Jira Ticket` to open the preferences dialog.

In iOS, tap the console icon in the home perspective, then tap the corresponding menu item.
