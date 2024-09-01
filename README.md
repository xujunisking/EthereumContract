## init step
## 1.npm init -y
## 2.npm install --save-dev hardhat
## 3.npx hardhat init
## 4.npx hardhat compile
## 5.npx hardhat node
## 6.npx hardhat ignition deploy ./ignition/modules/Lock.js --network localhost
## 7.npx hardhat clean
## 8.npx hardhat compile --force  (强制编译)

## installs fnm (Fast Node Manager)
winget install Schniz.fnm
## configure fnm environment
fnm env --use-on-cd | Out-String | Invoke-Expression
## download and install Node.js
fnm use --install-if-missing 18
## verifies the right Node.js version is in the environment
node -v # should print `v18.20.4`
## verifies the right npm version is in the environment
npm -v # should print `10.7.0`

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build