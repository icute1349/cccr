Ansible 과정 실습 환경설정
=====================

### 1. VirtualBox 다운로드 및 설치

#### Windows
[Windows] (https://download.virtualbox.org/virtualbox/6.0.4/VirtualBox-6.0.4-128413-Win.exe)  

#### macOS
[macOS] (https://download.virtualbox.org/virtualbox/6.0.4/VirtualBox-6.0.4-128413-OSX.dmg)  
또는
> brew cask install virtualbox virtualbox-extension-pack  

#### 공통
[VirtualBox Extendtion Pack] (https://download.virtualbox.org/virtualbox/6.0.4/Oracle_VM_VirtualBox_Extension_Pack-6.0.4.vbox-extpack)  

### 2. Vagrant 다운로드 및 설치

#### Windows
[Windows] (https://releases.hashicorp.com/vagrant/2.2.4/vagrant_2.2.4_x86_64.msi)  

#### MacOS
[macOS] (https://releases.hashicorp.com/vagrant/2.2.4/vagrant_2.2.4_x86_64.dmg)

### 3. Vagrant

#### 플러그인 설치  
> vagrant plguin install vagrant-hostmanager

#### Box 이미지 다운로드
> vagrant box add centos/7

#### Vagrant 파일
> cd  
> mkdir ansible  
> 