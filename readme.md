# Homebridge Doorbell plugin

homebridge-doorbell

## Installation

```
npm install -g jakorten/homebridge-doorbell
```

## Homebridge Config.json

```
"accessories" : [

    {
        "accessory": "Doorbell",
        "name": "Front door",
        "pin": 4,
        "reset": 4500
    }
]
```

| Key           | Description                                                                |
|---------------|----------------------------------------------------------------------------|
| accessory     | Required. Must be "doorbell"                                               |
| name          | Required. The name of this accessory.                                      |
| pin           | Required. The GPIO pin which will be raised when the doorbell is activated |
| reset         | Optional. Event reset timeout in ms. Default: 4500                         |
