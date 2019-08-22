# Threat.UML
A PlantUML addon for visualizing possible threats in a software or infrastructure
Based on the Ricardo Niepel's 4C template (https://github.com/RicardoNiepel/C4-PlantU

# Installation
To install and start useing the addon for Visual Studio Code, the following steps are needed:
1. Install Visual Studio Code ;-)
2. Install PlanUMl (Java needs to be installed). Run cmd.exe as Administrator, and run two commands as follow:
   ```
   @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object    System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

   choco install plantuml
   ```
   For the most Linux distributions are packages available.
 3. Clone the repo or extract the zip to your prject folder.
 
Done... Now you can use or replicate the templates.

## Snippet for Visual Studio Code

Because the PlantUML support inside of Visual Studio Code is excellent with the [PlantUML extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml), you can also find VS Code snippets for C4-PlantUML at [.vscode/C4.code-snippets](.vscode/C4.code-snippets).

Project level snippets are now supported in [VSCode 1.28](https://code.visualstudio.com/updates/v1_28#_project-level-snippets).
Just include the `C4.code-snippets` file in the `.vscode` folder of your project.

It is possible to save them directly inside VS Code: [Creating your own snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_creating-your-own-snippets).
