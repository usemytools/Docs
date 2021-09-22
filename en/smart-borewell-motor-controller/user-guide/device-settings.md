---
date: "2021-09-21"
author:
  display_name: "UseMyTools"
draft: "false"
toc: true
title: "Smart BoreWell Motor Controller and Timers – Device Settings"
description: "This section describes how to configure Smart borewell motor Controller and timers using its settings."
linktitle: "Device Settings"
menu:
  docs:
    identifier: "sbmc-device-settings"
    parent: "sbmc-user-guide"
    weight: "2"
lastmod: "2021-09-21"
weight: "1"
---

# Smart BoreWell Motor Controller and Timers – Device Settings #

We can configure Smart Motor Controller and Timers through its settings page.

**Device Menu -> Settings**

{{< figure src="../smart-borewell-motor-controller-device-settings.jpg" >}}

This setting page is used to configure system-level settings for Smart Motor Controller and Timers.

---

## Device Time ##

Device is using multiple sources like, RTC (Real Time Clock), NTP (Network Time Protocol), UseMyTools Time API to synchronize its clock machine. We easily update and run device time synchronization through time `Update` button.

{{< figure src="../smart-borewell-motor-controller-device-settings-time-update.jpg" >}}

---

## Device Reboot ##

Device can easily be rebooted using `REBOOT` button.

{{< figure src="../smart-borewell-motor-controller-device-settings-device-reboot.jpg" >}}

Note: It is recommended to reboot this tiny device once in few days.

---

## Device License ##

Device License can easily be update under `Device License` section.

Enter `Device License` as buy from [UseMyTools shop](https://shop.usemytools.net/product/smart-license/) and then click `Update`.

{{< figure src="../smart-borewell-motor-controller-device-settings-license-update.jpg" >}}

`Note`: System will verify device license and then enable its configuration accordingly. Device will auto reboot upon license update. Therefore, device is inaccessible for few seconds.

Once Device License is updated. Its information can been seen under `Device ID` section.

{{< figure src="../smart-borewell-motor-controller-device-settings-license-update-info.jpg" >}}

---

## Device Access Point Name ##

This setting will show device Access Point SSID that can been seen during Hotspot or configuration mode.

{{< figure src="../smart-borewell-motor-controller-device-settings-access-point-name.jpg" >}}

---

### Device Access Point AP Password ###

This setting will show device access point (AP) password that can used to connect with its Hotspot or during configuration mode.

{{< figure src="../smart-borewell-motor-controller-device-settings-access-point-password.jpg" >}}

We can change device access point (AP) password by entering new password and then click update.

{{< figure src="../smart-borewell-motor-controller-device-settings-access-point-password-update.jpg" >}}

---

### Device Reset Internet Settings ###

Device Internet Settings can be `reset` by using button. In this way, device will erase its last known Access Point Name and Password and enable its Hotspot to reconfigure the device network connection. This setting is useful to change device network or update existing new network credentials.

{{< figure src="../smart-borewell-motor-controller-device-settings-access-point-reset-internet-settings.jpg" >}}

---

## Device Wi-Fi Hotspot ##

This setting is used to enable/disable device wifi hotspot mode. Simply change the Wi-Fi Hotspot mode and then update it.

{{< figure src="../smart-borewell-motor-controller-device-settings-wi-fi-hotspot.jpg" >}}

---

## Use Device RTC ##

This settings is used to enable/disable to use device real-time clock (RTC) in wifi mode.

---

## Device Name ##

This setting is used to set Device Name. Enter new device name and then update it. Device Name is useful during Notification and tag your device with easy to remember name.

{{< figure src="../smart-borewell-motor-controller-device-settings-device-name.jpg" >}}

---

## Device Notification ##

This setting is used to enable/disable to send mobile notification from the device.

{{< figure src="../smart-borewell-motor-controller-device-settings-notification.png">}}

---

## Device Notification Test ##

This setting is used to test mobile notification from the device. Make sure `Device Notification` is enabled before performing this test.

{{< figure src="../smart-borewell-motor-controller-device-settings-notification-test.png">}}

---

## Device IoT Integration ##

This setting is used to enable/disable IoT (internet of things) Home Automation to control device from anywhere through internet.

{{< figure src="../smart-borewell-motor-controller-device-settings-iot.png">}}

---
