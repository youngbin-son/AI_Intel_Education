# AI_Intel_Education
### Linux Visual Studio Code Install
• Pre-packages Install
$ sudo apt update
$ sudo apt install software-properties-common apt-transport-https wget

• Get Microsoft GPG key
$ wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

• Add the apt repository for VSC
$ sudo add-apt-repository “deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main”

• VSC install
$ sudo apt install code

• Execution the VSC
& code
