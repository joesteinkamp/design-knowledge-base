# iPhone Technical Capability Report

## Hardware

### Accelerometer
Piece of hardware that can detect the device's 3D movement. It can detect if the device is tilting, rotating, shaken, flipped. 

Use Cases
- Detect movement to determine if the user is looking at the phone or not
- Pane the screen by moving the device
- Determine user interaction by tilting/rotating the phone (ex. Putting the phone face down)


### Front Facing Camera
This is an obvious one as I'm sure everyone has taken a selfie at some point. At its most basic function it is used for taking pictures but it can be used for more. The Front Facing Camera can be leveraged to see what's happening in front of the device. 

Use Cases
- Detect faces: a specific face, number of faces

### Rear Camera
Similar to the Front Facing Camera but with better quality. The placement also makes it be better at seeing what the user is seeing. The true power of the camera goes beyond taking photos. 

The cameras can be leveraged to analyze what is currently in view. For example, it can detect movement, scan barcodes, identify faces, identify retail products, and more. Don't be constrained by the idea that it's only for pictures. 

Use Cases
- Bar code scanner
- Product detection
- Face detection
- Motion sensor
- Camera


### Location Services (GPS, Wi-Fi, Cellular Network)
This might be the most powerful aspect of a phone. Location Services leverages the GPS, cellular network triangulation, and Wi-Fi to figure where the device is currently located. 

Often used in conjunction with Geofences. A Geofence is an area identified on a map that will tell the device to do something when the device enters or exits that area. 

### Bluetooth
A wireless device-to-device communication protocol that is often used for pairing other technology to the iPhone, such as headphones, speakers, pens (like Apple Pencil).

#### Beacons
Separate Bluetooth devices can be used to detect when a Bluetooth-enabled device is nearby and trigger an action on that nearby device if the appropriate app is installed to handle the trigger.


### Taptic Engine (Vibration Motor)
Everyone is extremely familiar with vibrations due to its usage in notifications and calls. But vibrations are an effective way to provide haptic feedback.

Dev References
https://developer.apple.com/library/ios/documentation/AudioToolbox/Reference/SystemSoundServicesReference/index.html


## Platform Integration

### Notifications

#### Interactive Notifications

#### Media Attachments

#### Customized In-App Notifications


#### Badging

https://developer.apple.com/design/human-interface-guidelines/ios/system-capabilities/notifications/
https://developer.apple.com/documentation/usernotifications
https://support.apple.com/en-us/HT201925



### Widget 
Currently, many apps support basic widgets but get little usage. Widgets are powerful mini apps that live within the Today View - a separate tab connected to Notifications Center. 

https://developer.apple.com/ios/human-interface-guidelines/extensions/widgets/


### Search API
Activity Indexing -> Spotlight integration

https://developer.apple.com/videos/play/wwdc2016/223/



### SiriKit
https://developer.apple.com/sirikit/

Use Cases
1. Ride Booking. Request a ride through apps that provide ride sharing and other taxi-like services.“Get me a ride to SFO via MyRidesApp.”
2. Messaging. Send text messages through apps that support messaging services.“Send a text to Carey using MyTextApp.”
3. Photo Search. Look for photos and videos of particular content type and play slideshows in the app of their choice.“Look for beach photos taken last summer in MyPhotosApp.”
4. Payments. Send and request payments to and from other people, using apps that support personal payments.“Send $100 to John for dinner last night using MyPayApp.”
5. VoIP Calling. Initiate video and audio calls with apps that support voice over IP.“Call Mike on my MyVoIPApp.”
6. Workouts. Start, pause and end workouts using your favorite workout app.“Start my daily run workout from MyWorkoutApp.”
7. Climate and radio. Specifically designed for CarPlay automaker apps, this allows users to set the climate controls and adjust the radio while they’re in their car.“Set the heater to 72 degrees.”



### ARKit


### Custom Keyboards


### Messages Extensions
https://developer.apple.com/design/human-interface-guidelines/ios/extensions/messaging/

### Sharing Extensions
https://developer.apple.com/design/human-interface-guidelines/ios/extensions/sharing-and-actions/

### Home Screen Quick Actions
https://developer.apple.com/design/human-interface-guidelines/ios/extensions/home-screen-actions/


### Safari View Controller (Android's Chrome Custom Tabs)
Ability to load a web browser inside your app and leverage Safari saved passwords. Supports displaying URLs without navigating the user away from your app and doesn't require development to build a web browser in your app.

Advantages
- Familiar UI
- Cookies shared from browser to app
- Autofill abilities (including passwords, credit cards, etc.)
- Same Share menu
- iOS
		○ Safari Reader
		○ Content Blocking

Customization
- Move "Done" to left or right of nav bar

Developer References
https://developer.apple.com/documentation/safariservices/sfsafariviewcontroller


### Spotlight Search Integration



## Permissions
- Notifications
- Contacts
- Calendar
- Reminders
- Motions & Fitness
- Health
- Location Services
- Camera
- Microphone
- Bluetooth
- Photos
- Background App Refresh
- HomeKit



## Additional iOS APIs

## Face and Barcode Detection in Images & Videos
https://developer.apple.com/documentation/coreimage/cidetector
