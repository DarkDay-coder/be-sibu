## Ubuntu installed

### sudo apt-get update
### sudo apt-get upgrade

### Google Chrome Installation
=> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
=> sudo dpkg -i google-chrome-stable_current_amd64.deb

### vs code installation 
=> sudo snap install --classic code

### git installation
=> sudo apt-get install git-all
=> git version

### node installation (older version)
=> sudo apt install nodejs npm
=> node -v
=> npm -v
This will install an older version of node

### node installation (new version)
=> sudo snap install curl 
=> curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
=> sudo apt install nodejs
IF ANY ERROR OCCURED TRY 
=> sudo dpkg -i --force-overwrite /var/cache/apt/archives/nodejs_18.12.1-deb-1nodesource1_amd64.deb
=> node -v
=> npm -v

### mongoDB installation
=> curl -fsSL https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
=> apt-key list
=> echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
=> sudo apt update
if error encountered (libssl error)
=> wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
=> sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb
=> sudo apt-get install -y mongodb-org

### mongoDBCompass installation
=> wget https://downloads.mongodb.com/compass/mongodb-compass_1.30.1_amd64.deb
=> sudo dpkg -i mongodb-compass_1.30.1_amd64.deb



## sudo apt --fix-broken install



### postman 
=> sudo apt install snapd
=> sudo snap install postman

## GIT configuration


