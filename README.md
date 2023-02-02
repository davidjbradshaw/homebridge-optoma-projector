# Homebridge Optoma Projector Telnet

A plugin for Homebridge, to control Optoma Projectors.

__This project is an unpublished work in progress__

## Configuration

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
  * `projectorId` (optional) - The ID of the projector (default value: `1`)
  * `model` (optional) - The projectors model (default value: `unkown`)
  * `serialNumber` (optional) - The projectors serial number (default value: `unknown`)
