# AI_Intel_Education
### 리눅스 Basic packages 추가
• 리눅스 패키지 설치법
   $ sudo apt install <package name> …
   
• 베이직 패키지 커맨드 입력
   $ sudo apt install -y build-essential software-properties-common vim terminator
gcc git git-all make cmake htop net-tools tree mplayer mesa-utils intel-opencl-icd
python3-dev python3-pip python3-setuptools python3-venv

### Linux Visual Studio Code Install
• Pre-packages Install
$ sudo apt update
$ sudo apt install software-properties-common apt-transport-https wget

• Get Microsoft GPG key
$ wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

• VSC를 설치하기 위한 저장소 추가
$ sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"

• VSC 설치
$ sudo apt install code

• Execution the VSC
& code
