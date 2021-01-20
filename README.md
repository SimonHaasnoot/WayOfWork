# Way Of Work
## Introduction
At Macaw we standardized our way of working where we strive for code quality, readability and quick project onboarding. This document will help you, the awesome Macaw employee, get up to speed and teach you in understanding our **way of work**.

## Document build-up
* Editor
* Extensions
* Configuration
* Code principles

## Editor
We work with [Visual Studio Code](https://code.visualstudio.com/). It is possible to use a different editor, but we highly recommend using this one (some extensions might for example not be available). This will make it easier for colleagues to help out if necessary.

## Extensions
Within Visual Studio Code we use a set of extensions where some are **required** for our code quality, productivity, formatting and testability.

### Required extensions
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
    * Helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
* [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
    * TSLint is an extensible static analysis tool that checks TypeScript code for readability, maintainability, and functionality errors.
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Prettier is a code formatter that enforces a consistent code style.
* [Vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
    * Provides comprehensive icons.
* [GitLens – Git Supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    * Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.
* [Code spell checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * Catch common spelling errors.

### Useful extensions
* [Live share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)
    * Real-time collaborative development
* [Bracket pair colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
    * This extension allows matching brackets to be identified with colours. The user can define which tokens to match, and which colours to use.
* [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
    * This extension shows version information of a package.
* [Markdown preview mermaid support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
    * Adds Mermaid diagram and flowchart support to VS Code's builtin markdown preview
* [TodoTree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
    * This extension quickly searches your workspace for comment tags like TODO and FIXME, and displays them in a tree view in the explorer pane.
* [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
    * XML Formatting, XQuery, and XPath Tools
* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
    * Provides comprehensive YAML Language support.

## Configuration

## Code principles
First, a bit of theory about the aspects of quality code. How can we achieve quality code, and what does this exactly mean?

Quality code consists out of the following 5 aspects:

1. Reliability
    Reliability measures the probability that a system will run without failure over a specific period of operation. It relates to the number of defects and availability of the software.
2. Maintainability
    Maintainability measures how easily software can be maintained. It relates to the size, consistency, structure, and complexity of the codebase. And ensuring maintainable source code relies on a number of factors, such as testability and understandability.
3. Testability
    Testability measures how well the software supports testing efforts. It relies on how well you can control, observe, isolate, and automate testing, among other factors.
4. Portability
    Portability measures how usable the same software is in different environments. It relates to platform independency.
5. Reusability
    Reusability measures whether existing assets — such as code — can be used again. Assets are more easily reused if they have characteristics such as modularity or loose coupling.

To translate the theory above to a **practical** approach; functions should, in almost all cases, live up to the following expectations:
* Small
* Easy to understand and read
* Be at 0 method extraction level
* Should always do one thing
* Indent level should not be greater than 2
* maximum number of arguments at around 3

