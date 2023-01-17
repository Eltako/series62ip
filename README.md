# Eltako SERIES 62-IP

This repository is the starting point for all things related to the Eltako SERIES 62-IP.
If you have questions, want to report a bug or request a feature that is not specific to another repository, then this is the right place to do so.

## What is the Eltako SERIES 62-IP
The brand new products that work with WiFi, are Apple Home certified and “built for Matter”. As soon as the Matter certification is available, the actuators will be delivered with this new standard directly from the factory.

## Tools

In the following we give a short summary of tools that may come in handy when working with Eltako SERIES 62-IP devices.

### Provision devices

There are multiple options to provision a device into a wifi network.
For Apple Homekit you should use the Apple Home App to do so.
For all other setups you may either use the Eltako Connect App or a command line utility.

* [Eltako Connect App for Android](https://play.google.com/store/apps/details?id=com.eltako.connect)
* [Command line utility](https://github.com/espressif/esp-idf/tree/edd815af2e/tools/esp_prov)

### Secure Communication with Devices

The Eltako SERIES 62-IP devices come pre-loaded with certificates used to secure the communication between the Eltako Connect App and the device.
You may want to do the same when communicating with the devices using your own means.

### Update Devices

The device checks automatically every 12 hours for an update.

### Communicate with Devices

The Eltako SERIES 62-IP devices feature a REST API which can be used to configure and control the device.
A postman collection is available at http://eltako.com/redirect/api-series-62-ip

:warning: The REST API is not finalized yet and may change in the future.
