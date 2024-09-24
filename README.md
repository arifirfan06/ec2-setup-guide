# Source

https://medium.com/@euricopaes/configure-nginx-with-a-wildcard-ssl-certificate-let-s-encrypt-65f951e0faa7

https://sirfitz.medium.com/setting-up-an-nginx-instance-with-certbot-and-configuring-it-for-wildcard-subdomains-on-ubuntu-96e413281a99

## Installation instructions

### 1. Open site location nginx console

### 2. ssh to ubuntu to install packages

```sh
ssh -i <key.pem> ubuntu@<ip-address> -v
```

### 3. Update and Upgrade linux machine and install node and nvm 

```sh
sudo apt update
```

```sh
sudo apt upgrade
```

```sh
sudo apt install -y git htop wget
```

#### 3.1 install node

To **install** or **update** nvm, you should run the [install script][2]. To do that, you may either download and run the script manually, or use the following cURL or Wget command:
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
Or
```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

