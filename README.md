## Prérequis pour installer l'environnement
* **Vagrant**
* **Virtualbox**

## Versions
* **Ubuntu 16-04** x64
* **Apache** 2.4.29
* **MySQL** 14.14
* **PHP** 7.1.11

## Installer l'environment
#### Cloner le projet
```
git clone git@github.com:girardthur/santevetServer.git
```
#### Modifier le fichier de configuration de la machine
```
 santevetServer\0tsffT\puphpet\config.yaml
```

L26 IP
```
private_network: 192.168.1.54
```

L46 Source project folder
```
source: 'c:/dev/santevet'
```

#### Lancer la machine 
```
vagrant up
```
```
vagrant ssh
```

### Installer curl
```
sudo apt-get install php-curl
```
