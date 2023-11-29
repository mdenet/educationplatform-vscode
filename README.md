# MDENet Education Platform
This extension contributes support for the [MDENet Education Platfom](https://github.com/mdenet/educationplatform-docker) configuration files. The goal of the Education Platform platform is to facilitate the teaching of Model-Driven Engineering by providing a web-based platform that requires no configuration and setup by learners. 

## Features
Tool and activity configuration file editor with syntax highlighting and code completion to assist in the creation of tools and activities for the MDENet education platform.

All files following with names following the patterns `*activity.json` and `*tool.json` will be validated.

## Installation
Currently, the extension has to be installed manually.
To do so, follow these steps:

1. Checkout the code and create a ZIP file of the complete folder. 
2. Open the ZIP file and ensure that the top-level folder is called `extension` and contains all the files in the root of the repository.
3. Rename the ZIP file to have extension `.vsix` instead of `.zip`.
4. Invoke `code --install-extension <PATH-TO-VSIX-FILE>`. VS Code should confirm successful installation of the extension and you should get code completion and syntax highlighting on the appropriate `.json` files.

## Using the Platform
- [Start a local instance of the platform and run some example activities](https://github.com/mdenet/educationplatform-docker)
- Documentation on [setting up the platform](https://github.com/mdenet/educationplatform/wiki/Setting-up-the-Platform)
- Documentation on [creating an activity](https://github.com/mdenet/educationplatform/wiki/Creating-an-Activity)
- Documentation on [creating a tool](https://github.com/mdenet/educationplatform/wiki/Adding-a-Tool)

## Issues
  Please report any issues found [here](https://github.com/mdenet/educationplatform-vscode/issues).


## License 
This project is licensed under the terms of EPL-2.0. Please refer to the [EPL-2.0](https://raw.githubusercontent.com/mdenet/educationplatform/main/LICENSE) for the full terms.