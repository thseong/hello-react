# Chapter 1

## Install

### Install Node.js using nvm

Install nvm:

```sh
$ brew install nvm
$ vim ~/.bash_profile
# Load nvm
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

Install Node.js:

```sh
$ nvm install --lts
```

### Install yarn

```sh
$ brew update
$ brew install yarn
$ yarn config set prefix ~/.yarn
$ echo 'export PATH="$(yarn global bin):$PATH"' >> ~/.bash_profile
```

## create-react-app

```sh
$ yarn create react-app hello-react
```

## Run

```sh
$ cd hello-react
$ yarn start
```
