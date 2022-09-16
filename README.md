## Power Converter

This script does two things:

- It takes [MQTT messages from the Shelly 3EM](https://shelly-api-docs.shelly.cloud/gen1/#shelly-3em-mqtt) and reposts them in the correct namespace.
- It takes MQTT messages from [lightstate](https://github.com/revspace/lichtknop/) and spacestate, figures out how much power consumption (when not measured by the Shelly 3EM) is associated with that, and also posts those in that same namespace
