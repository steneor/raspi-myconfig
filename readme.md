# Utilitaire de personnalisation de mon RPI STRETCH

Cet utilitaire regroupe différents scripts pour personnaliser mon **Raspberry PI raspbian strectch**

## Pour l'installer:
### méthode 1: (short URL via git.io)
    wget https://git.io/vp4EH -O /usr/local/sbin/raspi-myconfig
    chmod 700 /usr/local/sbin/raspi-myconfig
### méthode 1.1:
    wget https://raw.githubusercontent.com/steneor/raspi-myconfig/master/raspi-myconfig -O /usr/local/sbin/raspi-myconfig
    chmod 700 /usr/local/sbin/raspi-myconfig

### méthode 2:
    cd /tmp
    wget https://github.com/steneor/raspi-myconfig/archive/master.zip
    unzip master.zip
    cp -f raspi-myconfig-master/raspi-myconfig /usr/local/sbin/raspi-myconfig
    rm /tmp/master.zip
    rm -r /tmp/raspi-myconfig-master

### méthode 3:
    git clone https://github.com/steneor/raspi-myconfig

## Pour l'exécuter: raspi-myconfig
	raspi-myconfig

# Description des scripts:
## Menu sécurité
### Add utilisateur
### Del utilisateur pi
### Permit root login
### Update this tool
## Menu Logiciels
### Update Ugrade
### Install git
### Install samba
### Install LAMP
### Install wiringpi
### Install mail ssmtp
### Install logwatch
### Install webmin
## Menu Network
### IP fixe eth0
### IP fixe Wlan0
### IPV6 désactivation
### Mount freebox
