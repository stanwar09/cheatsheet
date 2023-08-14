```bash
sudo hostnamectl set-hostname jenkins
/bin/bash
```
```bash
sudo apt update
sudo apt install openjdk-17-jre -y
```
```bash
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
```
```bash
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
```
```bash
sudo apt-get update
sudo apt-get install jenkins -y
```
```bash
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```
```bash
systemctl status jenkins
```
