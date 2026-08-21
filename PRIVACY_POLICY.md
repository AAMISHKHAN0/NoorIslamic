# Privacy Policy for Noor (نور) — Islamic Prayer & Quran App

**Effective Date:** August 20, 2026  
**Last Updated:** August 20, 2026  
**App Name:** Noor: Prayer Times & Quran  
**Package Name:** `com.noor.islamic.app`  

---

## 1. Introduction
Welcome to **Noor** ("we", "our", or "us"). We are committed to respecting and protecting your privacy. This Privacy Policy explains how our mobile application handles user information and data when you use the Noor mobile application.

**Noor is designed as a privacy-first Islamic application. We do NOT sell, rent, or monetize your personal data.**

---

## 2. Information We Access and How It Is Used

### A. Location Information (Precise & Approximate Location)
* **What we access:** Geographic coordinates (Latitude and Longitude).
* **Why we need it:** 
  1. To calculate accurate daily prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha) tailored to your exact geographical location.
  2. To compute the precise directional angle (Qibla bearing) and distance to the Holy Kaaba in Makkah.
* **How it is processed:** Location data is processed locally on your device or ephemerally via secure HTTPS requests to standard prayer calculation APIs (e.g. AlAdhan API). **We do not track, log, store, or share your historical location data on any servers.**

### B. Device Sensors (Rotation Vector, Accelerometer, Magnetometer)
* **What we access:** Device orientation and magnetic field sensors.
* **Why we need it:** To operate the real-time interactive Qibla Compass so that the compass needle aligns with the Holy Kaaba as you rotate your phone.
* **How it is processed:** Sensor readings are processed purely in real-time in the device's volatile memory and are never saved or transmitted.

### C. Foreground Service & Notification Permissions
* **Why we need it:** To maintain continuous upcoming prayer status and countdowns in the system notification drawer, and to deliver exact prayer reminders and Adhan calls without being killed by Android battery optimization.
* **How it is processed:** Operates entirely locally on your device.

### D. Audio Features & Offline Storage
* **What we access:** Local device storage (`localStorage` / Cache).
* **Why we need it:** To save your user preferences (selected reciter, calculation method, dark/light theme, Dhikr Tasbih counts, saved Hadith bookmarks, and prayer tracker logs).
* **How it is processed:** Stored strictly locally on your own physical device.

---

## 3. Third-Party Services
Our application may use third-party APIs solely to fetch open-source Islamic content:
* **AlAdhan Prayer API:** Used ephemerally for coordinates-based prayer times and Hijri dates over encrypted HTTPS connections.
* **Quran Audio & Hadith Data:** Fetched over secure public CDNs.

These services do not receive any personally identifiable information (PII) from our app.

---

## 4. Children’s Privacy
Noor is suitable for users of all ages. We do not knowingly collect any personal information from children under the age of 13.

---

## 5. Security of Your Information
All network communications (such as fetching Quran audio or calculation tables) are strictly conducted over encrypted **HTTPS/TLS** connections.

---

## 6. User Data Control & Deletion
Because all your preferences, bookmarks, and Dhikr logs are stored locally on your device:
* You can clear all data at any time by going to **Settings > Clear App Data** within the app, or by clearing the app data in your Android device settings (**Settings > Apps > Noor > Clear Storage**).

---

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date.

---

## 8. Contact Us
If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us at:
* **Email:** digitalerena@gmail.com
* **Developer:** DigitalErena
* **Number:** +92 331 8768648
