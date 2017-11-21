siddhi-io-android
======================================

The **siddhi-io-android extension** is a collection of extensions to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that receives and publishes events to/from Android Device.
Using the extensions events can be received from different sensors available in android devices, events can be published as Notifications or Broadcast Intents.


Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-android">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-android/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-android/issues">Issue tracker</a>

## Latest API Docs

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT">1.0.0-SNAPSHOT</a>.

## How to use

**Using the extension with <a target="_blank" href="https://github.com/wso2/siddhi-android-platform">Siddhi Android Platform</a>**

* This extension can be added as a Gradle dependency along with other Siddhi dependencies to your Android project.

```
     dependencies {
        compile 'org.wso2.siddhi.io.android:siddhi-io-android:1.0.0-SNAPSHOT'
     }
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ |
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-io-android/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-io-android/) |

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-broadcast-sink">Android Broadcast</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink">Sink</a>)*<br><div style="padding-left: 1em;"><p>This will publish events arriving to the stream through android broadcasts intents which has attribute values as extras.</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-sound-sink">Android Sound</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink">Sink</a>)*<br><div style="padding-left: 1em;"><p>This will play android phone ringtone when ever it receives an event. It will played for a user specified time period</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-notification-sink">Android Notification</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink">Sink</a>)*<br><div style="padding-left: 1em;"><p>This will publish events arriving to the stream through android notifications</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-humidity-source">Android Humidity</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Humidity sensor of android device </p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-gravity-source">Android Gravity</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Gravity sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-linear-accelerometer-source">Android Linear Accelerometer</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Linear Accelerometer sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-pressure-source">Android Pressure </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Pressure sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-rotation-source">Android Rotation</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Rotation sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-light-source">Android Light </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Light sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-magnetic-source">Android Magnetic </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Magnetic sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-steps-source">Android Steps </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Steps sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-accelerometer-source">Android Accelerometer </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Accelerometer sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-game-rotation-source">Android Game Rotation</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Game Rotation sensor of android device</p></div>


* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-proximity-source">Android Proximity </a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Proximity sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-gyroscope-source">Android Gyroscope</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Gyroscope sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-broadcast-source">Android Broadcast</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Broadcast sensor of android device</p></div>

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-android/api/1.0.0-SNAPSHOT/#android-location-source">Android Location</a>*(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">Source</a>)*<br><div style="padding-left: 1em;"><p>This will receive events from Location sensor of android device</p></div>

## How to Contribute

  * Please report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-android/issues">GitHub Issue Tracker</a>.

  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-android/tree/master">master branch</a>.

## Contact us

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>.

 * Siddhi developers can be contacted via the mailing lists:

    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)

    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)

## Support

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology.

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>.
