# RokuDeployOnSaveVSCode

With help of vscode plugin "Run on Save" this setup will deploy the roku app on save.

# This has only been tested to work w/ MacOS

May need to update paths if using other OS such as Windows

# Installing

Install Run on Save extension:

```
https://marketplace.visualstudio.com/items?itemName=pucelle.run-on-save
```

## Install the extension from command line:

```
code pucelle.run-on-save-1.1.4.vsix
```

## Do not just copy over .vscode folder

It is better to let VS code create a settings.json for the works space.
Open code > preferences > settings
Click "Workspace" tab
Click top right button to open settings.json or search for settings.json

## Copy over settings.json

Change the settings.json to include your information
such as IP, paths, and passwords
