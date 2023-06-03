# NPM VS YARN
### *OR*
# NPM Equivalent of Yarn Commands

| NPM | YARN |
|-----------------|-----------------|
| npm init | yarn init |
| npm init -y | yarn init -y |
| npm i | yarn |
| npm i yourPackageName | yarn add yourPackageName |
| npm uninstall yourPackageName | yarn remove yourPackageName |
| npm run build | yarn build |
| npm install -g yourPackageName | yarn global add yourPackageName |

### Npm VS Yarn force install

| NPM | YARN |
|-----------------|-----------------|
| npm init --force | yarn init --force |
| npm i yourPackageName --force | yarn add yourPackageName --force |

### Npm VS Yarn development dependencies install

| NPM | YARN |
|-----------------|-----------------|
| npm install yourPackageName --save-dev | yarn add yourPackageName -D|

### Npm VS Yarn need for update

| NPM | YARN |
|-----------------|-----------------|
| npm install --global npm@latest | yarn set version yourVersionNumber |

#### Note:
If you need to use a specific npm version or if you need to switch from one version to another version a lot, you can use NVM. That is [Node Version Manager.](#https://github.com/nvm-sh/nvm)

### Npm VS Yarn need for clear

| NPM | YARN |
|-----------------|-----------------|
| npm cache clean | yarn cache clean|