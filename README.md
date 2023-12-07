# MDENet Education Platform
This extension contributes support for the [MDENet Education Platfom](https://github.com/mdenet/educationplatform-docker) configuration files. The goal of the Education Platform platform is to facilitate the teaching of Model-Driven Engineering by providing a web-based platform that requires no configuration and setup by learners. 

## Features
Tool and activity configuration file editor with syntax highlighting and code completion to assist in the creation of tools and activities for the MDENet education platform.

All files following with names following the patterns `*activity.json` and `*tool.json` will be validated.

Editing an activity configration file:
![gif showing the editing of an activity config](https://raw.githubusercontent.com/mdenet/educationplatform-vscode/main/images/editing-an-activity-config.gif?raw=true)

Editing a tool configuration file:
![gif showing the editing of a tool config](https://raw.githubusercontent.com/mdenet/educationplatform-vscode/main/images/editing-a-tool-config.gif?raw=true)

Listing the problems:
![gif showing the listing of problems](https://raw.githubusercontent.com/mdenet/educationplatform-vscode/main/images/showing-problems.gif?raw=true)

## Installation
Currently, the extension has to be installed manually. Either using a pre-packaged release or by building and packaging the source.

### Pre-packaged Release
 1. Download a `*.vsix` from [here](https://github.com/mdenet/educationplatform-vscode/releases).
 2. Install using a [cli](#install-via-the-command-line) or [VS Code](#install-via-vs-code)

#### Install via the command line
 2. Invoke `code --install-extension <PATH-TO-VSIX-FILE>`. 
 3. VS Code should confirm successful installation of the extension and you should get code completion and syntax highlighting on the appropriate `.json` files.

#### Install via VS Code
 2. Open VS Code and click View > Extensions.
 3. In the top right hand corner of the extensions panel which opens click the '...' button and from the sub-menu select 'Install from VSIX...'.
 4. In the dialog box that appears, navigate to the location of the vsix file downloaded in [1](#pre-packaged-release) and click install.

![gif showing extenstion install in vs code](https://raw.githubusercontent.com/mdenet/educationplatform-vscode/main/images/installing-vsix.gif?raw=true)

### Building from Source
To build the extension from source the following items are required and should be installed first: [Node JS](https://nodejs.org/en), [TypeScript](https://www.typescriptlang.org/), and [VSCE](https://code.visualstudio.com/api/working-with-extensions/publishing-extension).

1. Checkout the code. 
2. Invoke `vsce package` that will create a mdenet-education-platform-x.x.x.vsix file.
3. Follow [the steps](#pre-packaged-release) for installing the extension.


## Using the Platform
- [Start a local instance of the platform and run some example activities](https://github.com/mdenet/educationplatform-docker)
- Documentation on [setting up the platform](https://github.com/mdenet/educationplatform/wiki/Setting-up-the-Platform)
- Documentation on [creating an activity](https://github.com/mdenet/educationplatform/wiki/Creating-an-Activity)
- Documentation on [creating a tool](https://github.com/mdenet/educationplatform/wiki/Adding-a-Tool)

## Issues
  Please report any issues found [here](https://github.com/mdenet/educationplatform-vscode/issues).


## License 
This project is licensed under the terms of EPL-2.0. Please refer to the [EPL-2.0](https://raw.githubusercontent.com/mdenet/educationplatform/main/LICENSE) for the full terms.
