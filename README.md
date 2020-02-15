MixCloud Play
=====
MixCloud Play is the missing desktop experience for MixCloud.com with support for media controls and showing current track in menu bar. Enjoy listening your favorite music for hours...

## [Download for Mac](https://github.com/uffou/MixCloud-Play/releases/download/v0.9.1/MixCloud.Play.app.zip)

![screenshot](https://raw.githubusercontent.com/uffou/MixCloud-Play/master/Screenshot.png)

## Features
1. Media controls - play/pause, next
2. Menu bar track title
3. Song Notifications
4. Modern desktop look

## Getting started
```sh
yarn
yarn watch
yarn start
```

## Building
```sh
yarn dist
OR
yarn pack
```

## Docker
```sh
#curl --compressed -o- -L https://yarnpkg.com/install.sh | bash
docker-compose build
docker-compose run mixcloud-play yarn dist
```
Built app will output to ./dist/Mac/MMixCloud Play.app