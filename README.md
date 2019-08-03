# BackStr8 Object Detection Prototype
An desktop app using Electron that automatically detects human body and draws points and skeletons.

## Dependency

| Requirements | Version |
| ------------ | ------- |
| Node         | 10.16.0 |
| Electron     | 5.0.7   |
| npm          | 6.9.0   |


## Install nvm
```bash
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```

#### Install project

```bash
$ git clone "https://github.com/backstr8girls/obj_detection_prototype.git"
$ cd obj_detection_prototype
$ nvm install 10.16.0
$ echo "10.16.0" > .nvmrc
$ nvm use
$ npm i
```

#### Start project

```bash
$ npm run pack
```

Change directory to /dist/mac.
Double click file in it.