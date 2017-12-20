# figlet
## Description
http://www.figlet.org/
```
cd apps
./Figlet -f big.flf iExec
```
## Dapp params
```
module.exports = {
  name: 'Figlet',
  data: {
    type: 'BINARY',
    cpu: 'AMD64',
    os: 'LINUX',
  },
  work: {
    cmdline:'-f big.flf iExec',
    dirinuri:'http://www.figlet.org/fonts/big.flf',
  }
};
```
## [Examples](./examples)
