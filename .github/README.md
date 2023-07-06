# Chromium Code
A Code-OSS Fork designed to run on the Chromium Platform

## This Implements 
- everything needed to run code-oss directly in your browser as development platform
- Includes tooling for workdir and profile management
- Includes tooling for cloud-fs.zip and opfs.zip
- Includes NodeJS and Puppeteer For Compatability with the Legacy Ecosystems
- Includes AwesomeOS Extension Registry and AwesomeOS Private Extension Registry
- Includes AwesomeOS VSCODE Extension for InterOP with Existing Legacy VSCODE Forks and VSCODE It self.
- Includes Advanced AwesomeOS for Electron Developers GUIDE 

## Features
- Allows you to do Browser testing on a whole new Level via Integrating the Dev Environment into multiple Browsers
- Gives you better errors and Coding Expirence via Correct Error Messages that happen on development and in Production
  - Sounds Scary but today most systems report and produce different errors in development and production environments.

## Contributing
We take our own overriedes and source code from this chromium-code.git repo and some legacy dependencys from npm
We use the package-lock.json aus authoritativ file and update it via npm install 
We reduce redundancy and old code via the creation of additional modules inside /components/npm/package-name@version
so most best is to directly reference to /components/git/gitref github:orgOrName/repo#gitref

The npm command will try to install the package using git clone. The npm command can also install the package from different GitHub repository states using a commit hash value, which can be used to install the package with a commit id:

npm install use_name/node_project#commit
bash
Note: The @ symbol represents the npm scope, a technique to group all the dependencies of a user or org in a folder. A package name without @ and with name\name pattern will be treated as a GitHub package repository.

The branch name can be used to install a branch as a package:

npm install use_name/node_project#branch_name
bash
Similarly, the tag or version names can be used to install a specific version of a GitHub package:

npm install use_name/node_project@tag #user_name/node_project@release
npm install use_name/node_project@version #user_name/node_project@1.0.0
bash
gist can also be added using the id of a gist:

npm install gist/gist_id
