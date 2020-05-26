# Docker setup of Home Assistant

This project set up docket-compose image with Home Assistant, Mosquitto MQTT
and Zigbee2Mqtt.

## Notes
mosquitto password generated using:
sudo docker-compose run mosquitto mosquitto_passwd -c /mosquitto/config/mosquitto.passwd pi

