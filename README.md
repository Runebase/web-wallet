### NVM
```
apt-get update
apt-get install build-essential libssl-dev
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash
source ~/.profile

```

### Nodejs
```
nvm i v6
nvm use v6

```

### Base Install

#### Dev
```
git clone https://github.com/Runebase/web-wallet
cd web-wallet
npm i
npm install browserify -g

```


### Compiling for production

#### Webwallet bundle


```
browserify -t vueify -e src/wallet/main.js -o public/javascripts/wallet.js -v

```

