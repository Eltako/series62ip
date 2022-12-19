# Eltako Series 62 IP

This repository is the starting point for all things related to the Eltako Series 62 IP.
If you have questions, want to report a bug or request a feature that is not specific to another repository, then this is the right place to do so.

## What is the Eltako Series 62 IP

## Tools

In the following we give a short summary of tools that may come in handy when working with Eltako Series 62 IP devices.

### Provision devices

There are multiple options to provision a device into a wifi network.
For Apple Homekit you should use the Apple Home App to do so.
For all other setups you may either use the Eltako Connect App or a command line utility.

* [Eltako Connect App for Android](https://play.google.com/store/apps/details?id=com.eltako.connect)
* [Eltako Command-line Provisioning](https://github.com/Eltako/series62ip-provisioning)

### Secure Communication with Devices

The Eltako Series 62 IP devices come pre-loaded with certificates used to secure the communication between the Eltako Connect App and the device.
You may want to do the same when communicating with the devices using your own means.

* [Eltako Certificate Authority](https://github.com/Eltako/certificate-authority)

### Update Devices

There are multiple options to update a device:

* The device checks every 12 hours for an update
* Use the Eltako Connect App
* Use a command line script [Eltako Command-line Updater](https://github.com/Eltako/series62ip-updater)

The latter two options can be used if a device has no permanent internet connection.

### Communicate with Devices

The Eltako Series 62 IP devices feature a REST API which can be used to configure and control the device.
A postman collection is available at https://github.com/Eltako/series62ip-api.
However you may also use the compiled version available at TBD:

:warning: The REST API is not finalized yet and may change in the future.
