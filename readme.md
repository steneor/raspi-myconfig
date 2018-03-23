# Utilitaire de personnalisation de mon RPI strech

Cet utilitaire regroupe différents scripts pour personnaliser mon **Raspberry PI raspbian strectch**

## Pour l'installer:
### méthode 1:
    wget https://raw.githubusercontent.com/steneor/raspi-myconfig/master/raspi-myconfig -O /usr/local/sbin/raspi-myconfig
    chmod 744 /usr/local/sbin/raspi-myconfig
### méthode 2:
    cd /tmp
    wget https://github.com/steneor/raspi-myconfig/archive/master.zip
    unzip master.zip
    cp -f raspi-myconfig-master/raspi-myconfig /usr/local/sbin/raspi-myconfig
    rm /tmp/master.zip
    rm -r /tmp/raspi-myconfig-master
## Pour l'exécuter: raspi-myconfig
	raspi-myconfig

# Description des scripts:
## Menu sécurité
### Add utilisateur
### Del utilisateur pi
### Permit root login
### Update this tool
## Menu softs
### Update Ugrade
### Install git
### Install samba
### Install LAMP
### Install wiringpi
### Install mail smtp
### Install logwatch
### Install webmin
## Menu Hard
### IP fixe eth0
### IP fixe Wlan0
### Mount freebox
