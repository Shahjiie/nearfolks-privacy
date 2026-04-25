# Nearfolks — Privacy Policy

Last updated: April 25, 2026

---

## The Short Version

Nearfolks is built on one principle: your personal relationships are none of our business.

Every note, name, birthday, and memory you add stays on your phone. We have no servers.

We receive no data. We cannot read, sell, or lose what we never have.

---

## 1. Who We Are

Nearfolks is an Android application developed by Shahzaib Sultan. The app is a privacy-first personal relationship notebook — it helps you remember the people in your life without sending any information to us or anyone else.

Contact: shahzaibsulltan@gmail.com

---

## 2. Data We Collect

We collect nothing.

Nearfolks does not transmit any data to any server — ours or anyone else's. There is no account registration, no login, no cloud sync, and no analytics. The app makes zero network requests of its own.

---

## 3. Data Stored on Your Device

All information you enter — names, notes, birthdays, tags, reminders, quiz cards, and settings — is stored exclusively on your Android device in an encrypted local database (SQLCipher, AES-256 encryption). The encryption key is generated on first launch and stored in the Android Keystore, which is hardware-backed on supported devices.

This data never leaves your device unless you explicitly use the Export Backup feature, which writes a JSON file to your device's local storage. You control where that file goes.

If you uninstall the app, all data is permanently deleted from your device.

---

## 4. Permissions We Request

Nearfolks requests the following Android permissions. Each is requested only when you first use the feature that needs it — never at launch.

| Permission | Why |
|---|---|
| USE_BIOMETRIC / USE_FINGERPRINT | Optional app lock using your fingerprint or face |
| READ_CONTACTS | Contact import — lets you pick one contact via the system picker. We do not read your full contacts list. |
| RECORD_AUDIO | Voice notes — microphone input is transcribed on-device using Android's built-in SpeechRecognizer. Audio is never recorded or stored. |
| READ_CALENDAR | Smart Prep — reads your local calendar event titles to notify you before a meeting with someone you've added to Nearfolks. We never write to your calendar. |
| POST_NOTIFICATIONS | Smart Prep and reminder notifications |
| SCHEDULE_EXACT_ALARM / USE_EXACT_ALARM | Scheduling reminders at precise times |
| com.android.vending.BILLING | Required by Google Play for in-app purchases |

---

## 5. In-App Purchases

Nearfolks offers two optional one-time upgrades: Nearfolks Plus ($4.99) and Nearfolks Pro ($8.99). These are processed entirely by Google Play Billing.

When you make a purchase:

- Payment is handled by Google — we never see your card number or billing details.
- Google confirms the purchase to the app. The app stores your upgrade status locally in the encrypted on-device database.
- We do not operate a backend, so we cannot verify purchases server-side. Your purchase status is tied to your Google Play account for restore purposes.

For questions about billing, refunds, or purchase history, visit [Google Play Help](https://support.google.com/googleplay).

---

## 6. Third-Party Services

The only third party involved in running Nearfolks is Google Play — for app distribution and in-app billing. Google's own privacy policy applies to those interactions: https://policies.google.com/privacy

We do not integrate:

- Analytics (no Firebase, no Mixpanel, no Amplitude)
- Crash reporting (no Crashlytics, no Sentry)
- Advertising networks
- Social SDKs
- Any service that receives data about you or your usage

---

## 7. Voice & Speech

The voice notes feature uses Android's on-device SpeechRecognizer API. Audio is processed locally by Android — it is never streamed to a third-party server by Nearfolks.

Note: Android's own SpeechRecognizer may, on some devices, use Google's cloud speech service depending on your Android and Google app settings. This is outside our control.

To use fully offline voice recognition, ensure your device has an offline speech model installed in Android Settings → General Management → Language → Text-to-Speech.

---

## 8. Calendar Access

Smart Prep reads the titles and times of events from your local device calendar to check whether any upcoming event matches a person you've added to Nearfolks. This data is used only to generate a local notification. It is never stored in the database, never shared, and never leaves your device.

---

## 9. Children's Privacy

Nearfolks is not directed at children under the age of 13. We do not knowingly collect any information from children. Since we collect no data at all, no special handling is required — but parents should be aware the app stores data locally on the device.

---

## 10. Data Security

- Encryption at rest: Your database is encrypted with AES-256 via SQLCipher.
- Key management: The encryption key is stored in the Android Keystore.
- App lock: Optional biometric or PIN lock prevents unauthorized access.
- No transmission: There is nothing to intercept in transit because nothing is transmitted.

---

## 11. Your Rights

Since all data lives on your device, you have full control at all times:

- Access: Open the app — all your data is right there.
- Export: Use Settings → Export Backup to get a full JSON copy.
- Delete: Uninstall the app to permanently delete everything, or delete individual records within the app.
- Portability: Your exported JSON backup is a plain, human-readable file you can open in any text editor.

There is no account to close, no server to request deletion from, and no data retention period — because we hold nothing.

---

## 12. Changes to This Policy

If we add features that change how data is handled, this policy will be updated and the "Last updated" date at the top will change. Significant changes will be noted in the app's release notes.

---

## 13. Contact

If you have questions about this policy:

Shahzaib Sultan

contact@urduwriting.com

---

Nearfolks — Keep the people you love close, even when life gets busy.
