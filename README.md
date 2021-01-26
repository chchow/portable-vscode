# portable-vscode
This Visual Studio Code setup is for development environment for my required tools, such as NodeJS, Angular development, Java, Maven builds and Git.

## Steps to setup dev environment
1. Get required tools: Git, NodeJS, Java and Maven
2. Choose the terminal of your choice:<br>
  a. Setup for command prompt<br>
  b. Setup for powershell<br>
3. Git to use Windows Credential Manager

### 1. Get Tools
VSCode: Download .zip https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-archive <br>
Git: Download Git for Windows Portable ("thumbdrive edition") https://github.com/git-for-windows/git/releases/download/v2.30.0.windows.2/PortableGit-2.30.0.2-64-bit.7z.exe <br>
NodeJS: Download Windows Binary version zip https://nodejs.org/dist/v14.15.4/node-v14.15.4-win-x64.zip <br>
Java: Download JDK Windows x64 Compressed Archive version https://www.oracle.com/in/java/technologies/javase-jdk15-downloads.html#license-lightbox <br>
Maven: Download Binary zip archive https://downloads.apache.org/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.zip <br>
<br>
1. Extract VSCode to portable-vscode directory
2. Extract Git, NodeJS, Java and Maven into portable-vscode/tools/ directory; naming them git, nodejs, jdk, maven

### 2a. Setup command prompt
1. Copy command-prompt/add-tools-to-cmd.bat to portable-vscode/tools/ directory
2. Copy command-prompt/settings.json settings to VSCode settings.
3. Start VSCode and open command prompt. Check if the tools versions appears or try by testing the commands

### 2b. Setup powershell
1. Copy powershell/settings.json settings to VSCode settings.
2. Start VSCode and open command prompt. Check if the tools working try by testing the commands

### 3. Git to use Windows Credential Manager
Copy .gitconfig either from powershell or command-prompt into C:\Users\<user>\
