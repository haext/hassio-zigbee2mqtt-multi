# hassio-zigbee2mqtt-multi

<div align="center">
    <h1>Unofficial Zigbee2MQTT Home Assistant add-on for second instance</h1>
</div>

Based on https://github.com/zigbee2mqtt/hassio-zigbee2mqtt, this Home Assistant add-on allows you to run a second instance of Zigbee2MQTT.
This is necessary if you have more than one coordinator, such as for debugging or if you have a large number of devices.
This add-on is identical to [the official one](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt), and uses the exact same docker containers.
This add-on only exists because HomeAssistant cannot install one add-on two times, otherwise we wouldn't bother.
