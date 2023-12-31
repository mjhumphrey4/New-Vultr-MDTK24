# Vultr Markdown Toolkit (MDTK)

Vultr Markdown Toolkit (Vultr MDTK) is a helpful aid for creators who write content in the Markdown format. The Vultr MDTK consists of Vale style rules, the Vultr vocabulary, a recommended set of Visual Studio Code extensions, and a workspace file that sets the preferred defaults.

## How to Install the Vultr MDTK

1. Install the following required components on your workstation:

    * [Visual Studio Code](https://code.visualstudio.com/)
    * [Vale CLI](https://docs.errata.ai/vale/install)
    * [Vale Extension](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server)
    * [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    * [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

1. Clone the [vultr/vultr-mdtk](https://github.com/vultr/vultr-mdtk) repository to a directory on your workstation. Fpr example `Documents`.
1. Open the `vultr-mdtk.code-workspace` file using Visual Studio Code.

   > [!NOTE]
   > This workspace configures the correct options for Vale and all Markdown extensions.

1. Add and edit your Markdown files in the `Markdown` directory and verify that:

   * *Errors* are underlined in red
   * *Warnings* in yellow
   * *Suggestions* in blue.

    ![Popup Help](templates/media/Popup%20Help.png)

1. Open the *Problems* tab to view the complete list of scanned errors, warnings, and suggestions in your content.

    ![VSCode Example](templates/media/VSCode%20Example.png)

> ![NOTE]
> This README File is in Draft mode and it will be changed to an easy to follow guide in the first week of January 2024.