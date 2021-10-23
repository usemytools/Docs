---
date: "2021-09-21"
author:
  display_name: "UseMyTools"
draft: "false"
toc: true
title: "Smart Gas Controller and Timers – Device Settings"
description: "This section describes how to configure smart gas detector, alarm and notification using its settings."
linktitle: "Device Settings"
menu:
  docs:
    identifier: "sgd-device-settings"
    parent: "sgd-user-guide"
    weight: "2"
lastmod: "2021-09-21"
weight: "1"
---

# Smart Smoke Detector – Device Settings #

We can configure Smart Gas Detector, Alarm and Notification through its settings page.

**Device Menu -> Settings**

{{< figure src="../smart-gas-detector-device-settings.png" >}}

This setting page is used to configure system-level settings for Smart Gas Detector.

---

## Device Time ##

Device is using multiple sources like, NTP (Network Time Protocol), UseMyTools Time API to synchronize its clock machine. We easily update and run device time synchronization through time `Update` button.

{{< figure src="../smart-gas-detector-device-settings-time-update.jpg" >}}

---

## Device Reboot ##

Device can easily be rebooted using `REBOOT` button.

{{< figure src="../smart-gas-detector-device-settings-device-reboot.jpg" >}}

Note: It is recommended to reboot this tiny device once in few days.

---

## Device License ##

Device License can easily be update under `Device License` section.

Enter `Device License` as buy from [UseMyTools shop](https://shop.usemytools.net/product/smart-license/) and then click `Update`.

{{< figure src="../smart-gas-detector-device-settings-license-update.jpg" >}}

`Note`: System will verify device license and then enable its configuration accordingly. Device will auto reboot upon license update. Therefore, device is inaccessible for few seconds.

Once Device License is updated. Its information can been seen under `Device ID` section.

{{< figure src="../smart-gas-detector-device-settings-license-update-info.jpg" >}}

---

## Device Access Point Name ##

This setting will show device Access Point SSID that can been seen during Hotspot or configuration mode.

{{< figure src="../smart-gas-detector-device-settings-access-point-name.jpg" >}}

---

### Device Access Point AP Password ###

This setting will show device access point (AP) password that can used to connect with its Hotspot or during configuration mode.

{{< figure src="../smart-gas-detector-device-settings-access-point-password.jpg" >}}

We can change device access point (AP) password by entering new password and then click update.

{{< figure src="../smart-gas-detector-device-settings-access-point-password-update.jpg" >}}

---

### Device Reset Internet Settings ###

Device Internet Settings can be `reset` by using button. In this way, device will erase its last known Access Point Name and Password and enable its Hotspot to reconfigure the device network connection. This setting is useful to change device network or update existing new network credentials.

{{< figure src="../smart-gas-detector-device-settings-access-point-reset-internet-settings.jpg" >}}

---

## Device Name ##

This setting is used to set Device Name. Enter new device name and then update it. Device Name is useful during Notification and tag your device with easy to remember name.

{{< figure src="../smart-gas-detector-device-settings-device-name.jpg" >}}

---

## Device Notification ##

This setting is used to enable/disable to send mobile notification from the device.

{{< figure src="../smart-gas-detector-device-settings-notification.png">}}

---

## Device Notification Test ##

This setting is used to test mobile notification from the device. Make sure `Device Notification` is enabled before performing this test.

{{< figure src="../smart-gas-detector-device-settings-notification-test.png">}}

---

## Device IoT Integration ##

This setting is used to enable/disable IoT (internet of things) Home Automation to control device from anywhere through internet.

{{< figure src="../smart-gas-detector-device-settings-iot.png">}}

---

## Gas Leakage Detection Parameter ##

This settings is used to set which sensor parameter will be used for Gas Leakage Detection.

`Example: If Sensor Value is set then I will use raw sensor value for Gas Leakage Detection. You can also set PPM (Parts-per-million which is the ratio of one gas to another). Default is 'Sensor Value'.`

{{< figure src="../smart-gas-detector-settings-gas-leackage-detection-parameter.jpg">}}

---

## Sensor Threshold Value for Gas Detection ##

This settings is used to consider gas leakage detection if sensor value is above this threshold limit.

`Example: If you enter 200 then system will assume gas leackage detection when sensor value is above 200 and Gas Leakage Detection Parameter is set to 'Sensor Value'. Default Value is 200.`

{{< figure src="../smart-gas-detector-settings-gas-leackage-detection-threshold-value.jpg">}}

---

## PPM Threshold Value for Gas Detection ##

This settings is used to consider gas leakage detection if PPM value is above this threshold limit. PPM (Parts-per-million which is the ratio of one gas to another).

`Example: If you enter 2000 then system will assume gas leackage detection when sensor PPM value is above 2000 and Gas Leakage Detection Parameter is set to 'PPM Value'. Default Value is 2000.`

{{< figure src="../smart-gas-detector-settings-ppm-threshold-gas-leackage-detection.jpg">}}

---

## Room Ro Value ##

This settings is used for measurement of PPM calculation. R0 is the resistance of the sensor at a known concentration without the presence of other gases, or in fresh air.

{{< figure src="../smart-gas-detector-settings-room-ro-value.jpg">}}

---

## Room Ro Value - Auto calculate ##

This button is used to auto calculate the measurement of PPM. R0 is the resistance of the sensor at a known concentration without the presence of other gases, or in fresh air.

`Please Keep the Gas Sensor in clean air environment before using auto calculate method method. Default Ro value is 5.00`

{{< figure src="../smart-gas-detector-settings-room-ro-value-autocalculate.jpg">}}

---

## PPM M Value ##

This settings is used during PPM calculation(for Slop). Default is -0.318.

`Kindly throughly read Sensor Sensitivity Characteristics before changing it otherwise keep use default value.`

{{< figure src="../smart-gas-detector-settings-ppm-m-value.jpg">}}

---

## PPM B Value ##

This settings is used during PPM calculation(for Y-Intercept). Default is 1.133

`Kindly throughly read Sensor Sensitivity Characteristics before changing it otherwise keep use default value.`

{{< figure src="../smart-gas-detector-settings-ppm-b-value.jpg">}}

---

## Consecutive Notification Wait Time ##

This settings is used to set the wait limit before consecutive notification during Gas Leackage Detection. Default value is 5 minutes.

{{< figure src="../smart-gas-detector-settings-consecutive-notification-wait-time.jpg">}}

---

## Buzzer Notification ##

This settings is used to enable/disable to Buzzer notification from the device.

{{< figure src="../smart-gas-detector-settings-buzzer-notification.jpg">}}

---
