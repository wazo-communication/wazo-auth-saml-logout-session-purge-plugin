# wazo-auth-saml-logout-session-purge-plugin

Fixes wazo-auth saml logout session issue.

## Installation

```sh
wazo-plugind-cli -c 'install git https://github.com/wazo-communication/wazo-auth-saml-logout-session-purge-plugin.git'
```

Installing this plugin will restart `wazo-auth`, potentially impacting other services.

After installing this plugin, issues with SAML login following a failed logout will be fixed.

This plugin is only useful for Wazo servers between 24.13 and 24.15.

## Uninstallation

```sh
wazo-plugind-cli -c 'uninstall wazocommunication/wazo-auth-saml-logout-session-purge'
```
