# Privacy Policy — ZEPP Camera Shutter

**Last updated:** September 15, 2026

This Privacy Policy applies to:

- the **ZEPP Camera Shutter** mini program for Amazfit watches (Zepp OS), and
- the **ZEPP Camera Shutter** Android companion app (package `pl.maximus.camerashutter`; Polish display name: *Migawka aparatu ZEPP*).

Together, “the App” or “the Apps”.

---

## 1. Introduction

ZEPP Camera Shutter lets you remotely trigger the camera shutter on your phone from a compatible Amazfit watch. This policy explains what data we collect, how we use it, and your choices.

## 2. Data controller

**Maximus Apps**  
Privacy contact: [maximus.dev.apps@gmail.com](mailto:maximus.dev.apps@gmail.com)

## 3. What data we collect

We do **not** collect, store, or transmit personal data to our servers. We do **not** run analytics, advertising, or user profiling SDKs.

In particular, the Apps do **not** collect:

- name, email, or account credentials (the Apps do not create accounts),
- photos, camera frames, or microphone audio,
- contacts, location, or advertising identifiers,
- accessibility content for any purpose other than triggering the shutter (see below).

### Watch mini program

The mini program:

- communicates with the Zepp app on your phone via Side Service (Bluetooth),
- sends a **local** HTTP request only to the URL you configure (default: `http://127.0.0.1:18765` on your phone),
- may read basic device information (for example screen size) solely to lay out the user interface (permission `data:os.device.info`).

### Android companion

The companion app:

- listens **locally** on your phone (default port `18765`),
- does **not** send app data to the Internet for our processing,
- may use the Android **Accessibility** service **only** to trigger the shutter in an open camera app (for example by injecting VOLUME DOWN or tapping the on-screen shutter) — **only after you enable it** in Android Accessibility settings,
- may show a foreground notification while listening for watch commands.

Local preferences (for example listening on/off, autostart, trigger mode) are stored only on your device.

## 4. How we use data

Device information and local watch–phone communication are used solely to provide the remote shutter feature. We do not sell data or use it for advertising.

## 5. Data sharing

We do not sell or share personal data with third parties. Communication occurs between your watch, the Zepp app, and the companion app on your phone.

Third-party platforms you use to install the Apps (for example Google Play or Zepp) have their own privacy policies.

## 6. Storage and security

The Apps do not create cloud accounts and do not store personal data on our servers. You can stop listening, disable Accessibility, or uninstall the Apps at any time.

## 7. Children’s privacy

The Apps are not directed at children under 13, and we do not knowingly collect children’s personal data.

## 8. Your choices

- Uninstall the watch mini program and/or the Android companion.
- Disable Accessibility for ZEPP Camera Shutter in Android settings.
- Turn off listening / autostart in the companion app.
- Change or clear the companion URL in the Zepp mini program settings.

## 9. International users

Processing described here happens on your devices (watch and phone). We do not operate a backend that transfers your personal data internationally for this App.

## 10. Changes to this policy

We may update this Privacy Policy from time to time. The “Last updated” date at the top will change when we do. Continued use of the Apps after an update means you accept the revised policy.

## 11. Contact

Privacy questions: [maximus.dev.apps@gmail.com](mailto:maximus.dev.apps@gmail.com)
