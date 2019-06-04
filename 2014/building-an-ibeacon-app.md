[Building an iBeacon App](https://thenewstack.io/building-an-ibeacon-app/)
---

iBeacon is a protocol developed by Apple and is based on Bluetooth low energy proximity sensing by transmitting a universally unique identifier picked up by a compatible app or operating system. iBeacon can also be used with an application as an indoor positioning system.
---

Not all beacons are iBeacons. iBeacons are better. Make your feature compelling enough to get the user to turn on their bluetooth and location.

---

iBeacon monitoring is actually quite battery efficient.

---

Bluetooth beacons are radios. Radios are messy.

---

Protect your users’ personal info. Beacon regions count as location

---

Main Challenges:

Challenge #1: Choosing Features: Beacon technology allows your app to approximate its physical distance to the broadcasting beacon. You have to choose features that improve the app’s user experience, while still being realistic, protective of user trust, and if possible, still function without the beacons.

---

When choosing features, it’s important to keep in mind that when the app is in the background, even if it’s killed, the device still monitors for the presence of beacons (this is known as region monitoring)

---

Challenge #2: The Permission Matrix. The user needs to grant location permissions in order to use the feature.
In order to provide the best experience, you should wait until the last possible moment to ask for permission, instead of blasting users up front.

---

Challenge #3: Hardware. When using beacons, you have to be aware that you’re dealing with external radios. the signal quality depends on the broadcasting device (and we’ve found quality to vary wildly among manufacturers). it can take several minutes after the device leaves the broadcast zone to be considered outside the region.

---

Challenge #4: Triangulation & Tracking. Beacons are one-way devices, so they don’t know about the devices receiving their broadcasts. The easier way is to fake it by making the app do the work.

---

Challenge #5: The Server Piece. Determining presence at a beacon is tricky in the real-world because update events might not make it to the server and because beacon ranging can be dropped by an iOS device.

---

Challenge #6: Getting Through the App Store. It’s important to explain clearly what the app is doing, both in the public description and in the review notes. Since the app uses background location monitoring, we had to include a battery use disclaimer in our description.

Generally it's more difficult to convince Apple.

---

### About the Author

