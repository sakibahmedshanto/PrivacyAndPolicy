# Privacy Policy

**App Name:** RoboLink – Robot Controller  
**Developer:** Sakib Ahmed Shanto  
**Contact:** sakibahmedshanto15@gmail.com  
**Last Updated:** February 26, 2026  
**Effective Date:** February 26, 2026

---

## Introduction

Welcome to RoboLink ("the App"). This Privacy Policy explains how Sakib Ahmed Shanto ("I", "me", or "the Developer") handles information in connection with your use of the RoboLink Android application available on Google Play.

I am committed to protecting your privacy. This policy is designed to help you understand what permissions the App uses, why they are needed, and what data – if any – is collected or stored.

By downloading or using the App, you agree to the practices described in this Privacy Policy.

---

## 1. Information I Do NOT Collect

RoboLink is designed to operate entirely on-device and does **not**:

- Collect, transmit, or store any personal information on external servers.
- Create user accounts or require registration.
- Use advertising networks or display ads.
- Integrate with third-party analytics, tracking, or data-sharing SDKs.
- Sell, trade, or share any data about you with third parties.
- Access your contacts, photos, files, or any other personal data.

No data from your use of the App is ever sent to the Developer or any third party.

---

## 2. Information Stored Locally on Your Device

The App stores the following data **exclusively on your device's local storage**:

| Data | Purpose |
|---|---|
| Controller layouts | Save your custom widget configurations |
| Connection preferences | Remember Wi-Fi IP/port settings for quick reconnect |
| Paired device history | Cache previously connected Bluetooth device names/addresses for convenience |
| Widget settings | Store individual widget configurations (dead zones, axis ranges, labels, etc.) |

This data is stored locally using Android's standard storage APIs. It is never transmitted off your device and is deleted when you uninstall the App.

---

## 3. Permissions Used and Why

The App requests the following Android permissions. Each permission is used **only** for the stated purpose and for nothing else.

### 3.1 Bluetooth Permissions

| Permission | Android Version | Purpose |
|---|---|---|
| `BLUETOOTH` | Android 11 and below | Initiate and manage a Bluetooth Classic connection to your robot hardware (HC-05, HC-06, ESP32 Bluetooth) |
| `BLUETOOTH_ADMIN` | Android 11 and below | Discover and pair with Bluetooth devices |
| `BLUETOOTH_CONNECT` | Android 12+ | Connect to and communicate with paired Bluetooth robot hardware |
| `BLUETOOTH_SCAN` | Android 12+ | Scan for and discover nearby Bluetooth robot hardware |

**These permissions are used solely to establish a serial communication link between the App and your Arduino/ESP32 hardware. They are never used for tracking, advertising, or any purpose unrelated to robot control.**

### 3.2 Location Permissions

| Permission | Purpose |
|---|---|
| `ACCESS_FINE_LOCATION` | Required by Android OS (versions 6.0–11) to scan for nearby Bluetooth devices. Android mandates this permission for Bluetooth device discovery. The App does not use your physical location for any purpose and does not record, process, or transmit location data. |
| `ACCESS_COARSE_LOCATION` | Same as above – required by the Android system for Bluetooth scanning on Android 6.0–11. |

> **Important Note on Location:** Android requires apps to hold a location permission in order to scan for Bluetooth devices on Android 6.0 through 11. This is an Android platform requirement, not a choice by the Developer. The App does **not** determine, record, use, or share your physical location at any time.

### 3.3 Network / Wi-Fi Permissions

| Permission | Purpose |
|---|---|
| `INTERNET` | Send and receive control commands to your robot over a local Wi-Fi network using the UDP protocol |
| `ACCESS_NETWORK_STATE` | Check whether a network connection is available before attempting to connect |
| `ACCESS_WIFI_STATE` | Read Wi-Fi connection status to guide the user during setup |
| `CHANGE_WIFI_MULTICAST_STATE` | Required for UDP multicast discovery on some network configurations |

**All network communication takes place entirely on your local network (LAN). The App never communicates with any server on the internet.**

---

## 4. Camera / MJPEG Video Stream

The App supports displaying a live MJPEG video stream from an IP camera module installed on your robot. This is achieved by the App connecting to an HTTP stream URL that you provide (typically the local IP address of your ESP32-CAM or similar hardware).

- The App does **not** access the device's built-in camera.
- The live stream is displayed in real time inside the App and is **not** recorded, saved, or transmitted anywhere.
- The `CAMERA` hardware feature is **not** used or requested.

---

## 5. Children's Privacy

The App does not knowingly collect any personal information from children under the age of 13 (or the applicable age of digital consent in your jurisdiction). Since the App collects no personal information from any user, it is compliant with the Children's Online Privacy Protection Act (COPPA) and similar regulations.

If you believe your child has somehow submitted personal information through the App, please contact me at sakibahmedshanto15@gmail.com and I will take immediate steps to address it.

---

## 6. Data Security

Since RoboLink does not collect or transmit personal data to any server, the risk of a data breach affecting your personal information through this App is minimal. All data stored on your device is protected by your device's standard security mechanisms (screen lock, encryption, etc.).

---

## 7. Third-Party Services

The App itself does **not** include or use any third-party SDKs for advertising, analytics, crash reporting, or data collection. The app is self-contained.

This Privacy Policy does not apply to the Google Play Store through which you downloaded the App. Please review Google's Privacy Policy separately for information on how Google handles data.

---

## 8. Data Retention

All data created by the App (layouts, preferences, device history) is stored locally on your device and retained until you:

- Manually delete layouts or reset settings within the App, or
- Uninstall the App, which removes all associated local data.

The Developer retains no copies of any user data.

---

## 9. Your Rights

Since the App does not collect, process, or store any personal data on external servers, traditional data subject rights (access, deletion, portability, etc.) do not apply in the conventional sense.

If you have concerns about the data stored locally on your device, you can clear it at any time by:

- Clearing the App's local data via **Android Settings → Apps → RoboLink → Storage → Clear Data**, or
- Uninstalling the App.

---

## 10. Changes to This Privacy Policy

I may update this Privacy Policy from time to time to reflect changes in the App's functionality or applicable law. Any changes will be reflected by updating the "Last Updated" date at the top of this policy. I encourage you to review this policy periodically.

Continued use of the App after any changes constitutes your acceptance of the updated policy.

---

## 11. Contact

If you have any questions, concerns, or requests regarding this Privacy Policy or the App's data practices, please contact:

**Sakib Ahmed Shanto**  
Email: [sakibahmedshanto15@gmail.com](mailto:sakibahmedshanto15@gmail.com)

I will respond to all inquiries within a reasonable time.

---

## 12. Governing Law

This Privacy Policy is governed by applicable laws. Any disputes relating to this policy shall be resolved in accordance with the laws of the jurisdiction in which the Developer resides.

---

*This privacy policy was written to be fully compliant with Google Play Developer Policy requirements, including the User Data policy, Permissions policy, and Children and Families policy.*
