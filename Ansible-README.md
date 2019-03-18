Ansible 과정 실습 환경설정
=====================

### 1. VirtualBox 다운로드 및 설치

[Windows](https://download.virtualbox.org/virtualbox/6.0.4/VirtualBox-6.0.4-128413-Win.exe)  

[macOS](https://download.virtualbox.org/virtualbox/6.0.4/VirtualBox-6.0.4-128413-OSX.dmg)  
또는
> brew cask install virtualbox virtualbox-extension-pack  

[VirtualBox Extendtion Pack](https://download.virtualbox.org/virtualbox/6.0.4/Oracle_VM_VirtualBox_Extension_Pack-6.0.4.vbox-extpack)  

### 2. Vagrant 다운로드 및 설치

[Windows](https://releases.hashicorp.com/vagrant/2.2.4/vagrant_2.2.4_x86_64.msi)  
[macOS](https://releases.hashicorp.com/vagrant/2.2.4/vagrant_2.2.4_x86_64.dmg)

### 3. Vagrant

#### 플러그인 설치  
> vagrant plguin install vagrant-hostmanager

#### Box 이미지 다운로드
> vagrant box add centos/7

#### Vagrant 파일
> cd  
> mkdir ansible  
[Vagrantfile](https://raw.githubusercontent.com/c1t1d0s7/cccr/master/Ansible-Vagrantfile)  
> 파일 받아서 Vagrantfile로 저장  

### 4. Vagrant 사용법

상태확인  
> vagrant status  

시작  
> vagrant up  

일시중지  
> vagrant suspend  

재개  
> vagrant resume  

중지  
> vagrant halt  

삭제  
> vagrant destroy

SSH 연결
> vagrant ssh [host]