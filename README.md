# VPN-Web-Installer

Веб-интерфейс для установки/смены файлов конфигурации OpenVPN/WireGuard

# Установка
Чтобы установить локальный сайт на сервер введите сначала:
```bash
sudo apt-get install -y htop net-tools mtr dnsmasq network-manager wireguard openvpn apache2 php git iptables-persistent openssh-server resolvconf speedtest-cli nload libapache2-mod-php
```
А затем эту команду чтобы скачать файлы сайта:
```bash
sudo git clone https://github.com/Rostarc/VPN-Web-Installer.git /var/www/html
```
Чтобы войти на него перейдите по своему локальному адресу  http://192.168.X.X/ из компьютера в локальной сети
