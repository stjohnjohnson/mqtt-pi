# MQTT for Raspberry Pi

## Installation
Depends on `pm2`

```
$ npm install -g pm2
```

## Usage

### Locally
```
$ npm install
$ pm2 startOrRestart ecosystem.json
```

### Remotely

```
$ pm2 deploy ecosystem.json prod
```
