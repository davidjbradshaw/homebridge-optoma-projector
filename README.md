# Homebridge Optoma Projector

A plugin for Homebridge, to control Optoma Projectors via Telnet.

## Installation and configuration

Install via the HomeBridge UI or via the command line:

```
sudo npm install homebridge-optoma-projector
```

Add your projector in your Hombridge `config.js`:

```
"accessories": [
    {
        "accessory": "OptomaProjectorTelnet",
        "name": "My Projector",
        "address": "10.0.0.90"
    }
]
```

### Settings

  * `accessory` - has to be `OptomaProjectorTelnet`
  * `name` - the accessories name
  * `address` - IP address of the projector
  * `port` (optional) - Telnet port of the projector (default value: `23`)
  * `pollInterval` (optional) - Projector status polling interval in seconds (default value: `1`,  disable: `0`)
  * `projectorId` (optional) - The ID of the projector (default value: `1`)
  * `model` (optional) - The projectors model (default value: `unkown`)
  * `serialNumber` (optional) - The projectors serial number (default value: `unknown`)
  * `logLevel` (optional) - 0: off, 1: default, 3: verbose (default value: `1`)
