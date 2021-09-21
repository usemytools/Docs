---
date: "2020-03-09"
author:
  display_name: "UseMyTools"
draft: "false"
toc: true
title: "Smart Tank Controller – Device Settings"
description: "This section describes how to configure Smart water storage tank level Controller using its settings."
linktitle: "Device Settings"
menu:
  docs:
    identifier: "stc-device-settings"
    parent: "stc-user-guide"
    weight: "3"
lastmod: "2020-03-09"
weight: "1"
---

# Smart Tank Level Controller – Device Settings #


We can configure Smart Tank Level Controller through its settings page.
**Device Menu -> Settings**

{{< figure src="../smart-tank-level-controller-device-settings.jpg" >}}

This setting page is used to configure system-level settings for Smart Tank Level Controller.

---

## Device Time ##

Device is using multiple sources like NTP (Network Time Protocol), UseMyTools Time API to synchronize its clock machine. We easily update and run device time synchronization through time `Update` button.

{{< figure src="../smart-tank-level-controller-device-settings-time-update.jpg" >}}

---

## Device Reboot ##

Device can easily be rebooted using `REBOOT` button.

{{< figure src="../smart-tank-level-controller-device-settings-device-reboot.jpg" >}}

Note: It is recommended to reboot this tiny device once in few days.

---

## Device License ##

Device License can easily be update under `Device License` section.

Enter `Device License` as buy from [UseMyTools shop](https://shop.usemytools.net/product/smart-license/) and then click `Update`.

{{< figure src="../smart-tank-level-controller-device-settings-license-update.jpg" >}}

`Note`: System will verify device license and then enable its configuration accordingly. Device will auto reboot upon license update. Therefore, device is inaccessible for few seconds.

Once Device License is updated. Its information can been seen under `Device ID` section.

{{< figure src="../smart-tank-level-controller-device-settings-license-update-info.jpg" >}}

---

## Device Access Point Name ##

This setting will show device Access Point SSID that can been seen during Hotspot or configuration mode.

{{< figure src="../smart-tank-level-controller-device-settings-access-point-name.jpg" >}}

---

### Device Access Point AP Password ###

This setting will show device access point (AP) password that can used to connect with its Hotspot or during configuration mode.

{{< figure src="../smart-tank-level-controller-device-settings-access-point-password.jpg" >}}

We can change device access point (AP) password by entering new password and then click update.

{{< figure src="../smart-tank-level-controller-device-settings-access-point-password-update.jpg" >}}

---

### Device Reset Internet Settings ###

Device Internet Settings can be `reset` by using button. In this way, device will erase its last known Access Point Name and Password and enable its Hotspot to reconfigure the device network connection. This setting is useful to change device network or update existing new network credentials.

{{< figure src="../smart-tank-level-controller-device-settings-access-point-reset -internet settings.jpg" >}}

---

## Device Wi-Fi Hotspot ##

This setting is used to enable/disable device wifi hotspot mode. Simply change the Wi-Fi Hotspot mode and then update it.

{{< figure src="../smart-tank-level-controller-device-settings-wi-fi-hotspot.jpg" >}}

---

## Device Name ##

This setting is used to set Device Name. Enter new device name and then update it. Device Name is useful during Notification and tag your device with easy to remember name.

{{< figure src="../smart-tank-level-controller-device-settings-device-name.jpg" >}}

---

## Device Notification ##

This setting is used to enable/disable to send mobile notification from the device.

{{< figure src="../smart-tank-level-controller-device-settings-notification.png">}}

---

## Device Notification Test ##

This setting is used to test mobile notification from the device. Make sure `Device Notification` is enabled before performing this test.

{{< figure src="../smart-tank-level-controller-device-settings-notification-test.png">}}

---

## Device IoT Integration ##

This setting is used to enable/disable IoT (internet of things) Home Automation to control device from anywhere through internet.

{{< figure src="../smart-tank-level-controller-device-settings-iot.png">}}

---

## Tank Height ##

This setting is used to set measurement of water tank in cm (centimeters).

{{< figure src="../smart-tank-level-controller-device-settings-tank-height.jpg">}}

---

## Sensor Top Height ##

This setting is used to set measurement of sensor height from the top of tank height in cm (centimeters). Please subtract sensor length from the height.

`Example:  If Sensor Height from top of tank is 13cm and sensor lenght is 5cm then your sensor top height is 13 - 5 = 8cm`

{{< figure src="../smart-tank-level-controller-device-settings-sensor-top-height.jpg">}}

---

## Tank Full Threshold limit ##

This setting is used to consider tank is full at this percentage threshold limit value.

`Example: If you enter 88 then system will assume tank is consider to be full when it is filled upto 88%. Please also keep in mind that sensor need minimum of 22cm of distance to give accurate reading.`

{{< figure src="../smart-tank-level-controller-device-settings-tank-full-threshold-limit.jpg">}}

---

## Tank Empty Threshold limit ##

This setting is used to consider tank is empty at this percentage threshold limit value.

`Example: If you enter 20 then system will assume tank is consider to be empty when it is reached by this % level (20%).`

{{< figure src="../smart-tank-level-controller-device-settings-tank-empty-threshold-limit.jpg">}}

---

## Ignored Blind Zone Reading Value ##

This setting is used to set the value till that system will consider as Blind Zone and ignore all those reading to imporve accuracy.

`Example: If you enter 20 then system will assume all sensor reading till 20cm will be consider as Blind Zone and will be ignored.`

{{< figure src="../smart-tank-level-controller-device-settings-ignored-blind-zone-reading-value.jpg">}}

---

## Motor Integration ##

This setting is used to enable/disable integration of motor device.

{{< figure src="../smart-tank-level-controller-device-settings-motor-integration.jpg">}}

---

### Integrated Motor Device ###

This setting is used to set Integrated Motor Device license.

{{< figure src="../smart-tank-level-controller-device-settings-integrated-motor-device.jpg">}}

---

### Integrated Motor Device Name ###

This setting is used to set the integrated motor device name which is used at the time of send mobile notification regarding integrated motor device.

{{< figure src="../smart-tank-level-controller-device-settings-integrated-motor-device-name.jpg">}}

---

### Integrated Motor Device Switch ###

This setting is used to select the switch which will turn on/off of integrated motor device.

{{< figure src="../smart-tank-level-controller-device-settings-integrated-motor-device-switch.jpg">}}

---

### Integrated Motor Device Switch Test ###

This setting is used to test turn on/off switch of integrated motor device.

{{< figure src="../smart-tank-level-controller-device-settings-integrated-motor-device-switch-test.jpg">}}

---

### Notify Integrated Motor Upon Full ###

This setting is used to notify integrated motor device to turn off when tank is reach at its full threshold limit.

{{< figure src="../smart-tank-level-controller-device-settings-notify-integrated-motor-upon-full.jpg">}}

---

### Notify Integrated Motor Upon Full Test ###

This setting is used to test notify integrated motor device to turn off when tank is reach at its full threshold limit.

{{< figure src="../smart-tank-level-controller-device-settings-notify-integrated-motor-upon-full-test.jpg">}}

---

### Notify Integrated Motor Upon Low ###


This setting is used to notify integrated motor device to turn on when tank is reach at its low threshold limit.

{{< figure src="../smart-tank-level-controller-device-settings-notify-integrated-motor-upon-low.jpg">}}

---

### Notify Integrated Motor Upon Low Test ###

This setting is used to test notify integrated motor device to turn on when tank is reach at its low threshold limit.

{{< figure src="../smart-tank-level-controller-device-settings-notify-integrated-motor-upon-low-test.jpg">}}

---

### Consecutive Reading Limit before Notify ###


This setting is used to set the number of consecutive threshold limit reading count before notify integrated motor device to perform action. Default value is 5.

{{< figure src="../smart-tank-level-controller-device-settings-consecutive-reading-limit-before-notify.jpg">}}

---
### Enable Wait Period After Consecutive Integrated Notification ###


This setting is used to enable wait period after consecutive notify to integrated motor device to perform action. Default value is true.

{{< figure src="../smart-tank-level-controller-device-settings-enable-wait-period-after-consecutive-integrated-notification.jpg">}}

---

### Consecutive Integrated Notify Count before waiting ###

This setting is used to set the number of threshold limit of consecutive notify to integrated motor device to perform action before start Waiting Period. Default value is 3.

{{< figure src="../smart-tank-level-controller-device-settings-consecutive-integrated-notify-count-before-waiting.jpg">}}

---

### Waiting Time Period after Consecutive Integrated Notify ###

This setting is used to set the wait period after consecutive notify to integrated motor device to perform action. Default value is 10 minutes.

{{< figure src="../smart-tank-level-controller-device-settings-waiting-time-period-after-consecutive-integrated-notify.jpg">}}

---

## DryRun Motor Integration ##

This setting is used to enable/disable to DryRun motor integration.

{{< figure src="../smart-tank-level-controller-device-settings-dryrun-motor-integration.jpg">}}

---

### DryRun Notification ###

This setting is used to enable/disable to send mobile notification related to DryRun feature.

{{< figure src="../smart-tank-level-controller-device-settings-dryrun-notification.jpg">}}

---

### DryRun Cut-off Period Time ###

This setting is used to set the recurring wait period before performing DryRun related action. Default value is 5 minutes.

{{< figure src="../smart-tank-level-controller-device-settings-dryrun-cut-off-period-time.jpg">}}

---

### DryRun Pre-Ignored Waiting Period Time ###

This setting is used to set the initial wait period at the start of DryRun. Default value is 0 minutes.

`Example: If you set Pre-Ignored Waiting Period to 3 minutes and your DryRun Cut-off Period is 5 minutes. Then first DryRun check will be performed after 8 minutes of Waiting time upon Integrated Motor start and afterwards DryRun check will be performed after 5 minutes each.`

{{< figure src="../smart-tank-level-controller-device-settings-dryrun-pre-ignored-waiting-period-time.jpg">}}

---

### DryRun Cut-off Tank Reading ###

This setting is used to set the minimum cut-off incremented tank reading to bypass DryRun detection. Default value is 2 cm.

{{< figure src="../smart-tank-level-controller-device-settings-dryrun-cut-off-tank-reading.jpg">}}

---

### Max DryRun Count ###

This setting is used to set the number of threshold limit of consecutive period of DryRun detection count before performing action. Default value is 2.

{{< figure src="../smart-tank-level-controller-device-settings-max-dryrun-count.jpg">}}

---

### Notify Integrated Motor Upon DryRun Detection ###

This setting is used to notify integrated motor device to turn off when tank has detected DryRun and consecutive Max DryRung count threshold limit has been reached.

{{< figure src="../smart-tank-level-controller-device-settings-notify-integrated-motor-upon-dryrun-detection.jpg">}}

---

## Tank Volumes Factor ##

This setting is used to estimate the tank fill volumes by using volumes factor (in cubic cm). Only supports Vertical Cylinder or Rectangle Tank. Set 0 to disable it.

`Example: For Vertical Cylinder Tank, V(fill) = πr2f and its volumes factor will be πr2. For Rectangle Tank, V(fill) = lwf and its volumes factor be lw.`

{{< figure src="../smart-tank-level-controller-device-settings-tank-volumes-factor.jpg">}}

---

## Smart Tank Level Controller - Demo ##

[Smart Tank Level Controller - Demo Video](https://youtu.be/UfZzu6t3mNo)

{{< youtube UfZzu6t3mNo >}}
