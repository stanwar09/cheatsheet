```bash
sudo hostnamectl set-hostname sonarqube
/bin/bash
```
```bash
sudo apt update
sudo apt install openjdk-17-jre -y
```
```bash
wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-10.1.0.73491.zip
```
```bash
unzip sonarqube-10.1.0.73491.zip 
```
```bash
cd sonarqube-10.1.0.73491/
```
```bash
cd bin
```
```bash
cd linux-x86-64/
```
```bash
./sonar.sh console
```
