# Rich Notification SDK

[![Latest Stable Version](https://img.shields.io/badge/version-1.1.3-green.svg)](http://developer.samsung.com/galaxy/rich-notification)

> __Note:__ 

> We regret to inform you that the Pass SDK will no longer provide DEVICE_FINGERPRINT_UNIQUE_ID for Samsung mobile devices starting from the second half of this year. We will no longer be providing a list of indexes and unique IDs for each registered fingerprint. Therefore, you will not be able to distinguish which fingerprints are used to verify the user.

The goal of the Rich Notifications SDK is to offer a way for developers to reach users with a minimal amount of effort. It provides the flexibility to personalize and brand content, making it compelling and actionable.

__Design Principles__

Rich Notifications have the following characteristics:

__Glance-able__: Rich Notifications are a lightweight way for service providers to send updates to users in real-time. They are concise and informative, offering bite-sized updates that highlight the most important details at a glance.

__Actionable__: Actions are placed on the top level of Rich Notifications, allowing users to take control with single touch. Users can quickly perform actions such as responding to a message, navigating to a destination, or liking a photo without having to pull out their phone or dig through Apps.

__Delightful__: Rich Notifications were designed with personalization in mind. They support full color graphics, rich text, and flexible content layouts. They offer a stylish and engaging interface for users to interact with their favorite services.

__Content Structure__

A standard notification is made of the following components:

![Rich Notification](http://developer.samsung.com/sd2_images/galaxy/content/img_richnotification01.jpg)

__Tap to View More Details__

Developers have the option to include secondary content with any notification. This content will be shown when the user taps on the body of the notification

![Rich Notification 2](http://developer.samsung.com/sd2_images/galaxy/content/img_richnotification02_160118.jpg)

__Actions__

Actions are an important part of Rich Notifications. They allow users to engage with the content and perform tasks. There are two types of Actions: Primary Actions and More Options.

__Primary Actions__

Primary Actions are the most important action associated with the notification. These actions can work in one of two ways: single tap and a selectable list of commands.


![Rich Notification 3](http://developer.samsung.com/sd2_images/galaxy/content/img_richnotification03_160118.jpg)

__More Options__

The “More Options” icon produces a menu of additional actions that the user might want to take on the notification. These options are less accessible by design, placing the emphasis on the Primary Action.

![Rich Notification 4](http://developer.samsung.com/sd2_images/galaxy/content/img_richnotification04.jpg)

__Templates__

Developers can choose from a variety of templates that provide alternative visual layouts and content structures. There are two types of templates: Primary and Secondary.

![Rich Notification 5](http://developer.samsung.com/sd2_images/galaxy/content/img_richnotification06_160118.jpg)

Restrictions

Rich Notification SDK has the following restrictions:

- Devices with Android 4.4 KitKat (API level 19) or higher support Rich Notification SDK.
- Rich Notification SDK requires Gear Manager to connect Wearable Device.

## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:samsung-services-pass:1.1.3'
}
```

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
