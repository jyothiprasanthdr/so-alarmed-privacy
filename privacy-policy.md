# Privacy Policy for So Alarmed

**Last updated: June 28, 2026**

This Privacy Policy explains how **So Alarmed** ("the App", "we", "us", or "our") collects, uses, stores, and protects your information. So Alarmed is an alarm-clock app for iPhone that wakes you up and asks you to complete a short "wake-up mission" before the alarm will stop.

The App is developed and operated by **Nandha Kumar Ilangovan** ("the Developer"), who is the data controller responsible for your information under this Policy.

We built So Alarmed to be **privacy-first**. We do **not** run ads, we do **not** use analytics or tracking SDKs, we do **not** collect crash reports, and we do **not** sell or share your personal information for advertising. Most of your data never leaves your device. By using the App, you agree to this Privacy Policy.

---

## 1. Summary (the short version)

- The App works fully **offline** and **without an account**. Your alarms, settings, and wake-up streak are stored **on your device**.
- Signing in is **optional**. If — and only if — you choose to sign in with **Apple** or **Google**, we create an account so we can **back up your alarms and streak** and restore them on your other devices.
- We use **Apple StoreKit** for the optional paid subscription. We never see or store your card or payment details.
- The "Shake" and "Walk" wake-up missions read your phone's **motion sensors in real time, on your device only**. This motion data is **never stored and never transmitted**.
- We do **not** collect location, contacts, photos, camera, microphone, health, or advertising data.
- We do **not** use analytics, advertising, or third-party tracking of any kind.
- You can **delete your account and all backed-up data** at any time from within the App (Settings → Delete account).

---

## 2. Information We Collect

We only collect what the App needs to function. Below is everything.

### 2.1 Information stored only on your device (not collected by us)

When you use the App without signing in, the following stays **on your device** and is **not** transmitted to us or anyone else:

- **Your alarms** — for each alarm: the time, an optional label you type, the chosen alarm sound, the chosen wake-up mission, the difficulty, the repeat days, and whether the alarm is on or off.
- **Your wake-up streak** — the calendar dates on which you successfully completed a mission and dismissed an alarm.
- **App preferences and state** — such as whether you have finished onboarding and your subscription status (see Section 2.4).

If you never sign in, none of the above leaves your device.

### 2.2 Account information (only if you choose to sign in)

Signing in is optional and exists only to back up and sync your data. If you sign in using **Sign in with Apple** or **Sign in with Google**, we receive and store the following through Google Firebase Authentication:

- A unique **account identifier** (user ID) assigned to your account.
- Your **name**, if your sign-in provider shares it.
- Your **email address**. If you use Sign in with Apple, you may choose Apple's **private email relay**, in which case we only ever receive a relay address, not your real email.
- Which **sign-in provider** you used (Apple or Google).

### 2.3 Backed-up data (only if you choose to sign in)

When you are signed in, the App backs up the following to your private cloud record so it can be restored on your other devices:

- Your **alarms** (the same fields described in Section 2.1).
- Your **wake-up streak** dates.
- Your **onboarding completion** status.

This backup happens only while you are signed in. If you sign out or never sign in, this data is not uploaded.

### 2.4 Subscription information

So Alarmed offers an optional paid subscription handled entirely by **Apple's App Store / StoreKit**. We receive from Apple only your **subscription status** (for example, whether you have an active subscription or trial) so the App can unlock paid features. We do **not** receive or store your name, card number, billing address, or any payment details — Apple handles all of that. Your subscription status is cached **on your device only** and is never sent to our cloud.

### 2.5 Motion sensor data (used live, never stored)

Two optional wake-up missions use your iPhone's motion sensors:

- The **Shake** mission reads the **accelerometer** to detect shaking.
- The **Walk** mission reads the **pedometer (step counter)** to count steps.

This motion data is processed **in real time on your device only**, used solely to verify you completed the mission, and is **immediately discarded**. It is **never stored, never logged, and never transmitted** anywhere. iOS will ask your permission before these sensors are used, and you can revoke that permission at any time in the iOS Settings app. If motion access is unavailable, these missions fall back to a tap-based alternative.

### 2.6 Notifications

So Alarmed schedules alarms using Apple's **AlarmKit** (on iOS 26 and later) and local notifications. These are created and delivered **on your device by iOS**. We do **not** operate a push-notification server, and we do **not** send your data anywhere to deliver an alarm. If you start a free trial, the App may schedule a **local** reminder notification before the trial ends; this contains no personal data.

### 2.7 What we do NOT collect

For clarity, So Alarmed does **not** collect any of the following:

- Precise or approximate **location**
- **Contacts**, **calendar**, **photos**, **camera**, or **microphone** data
- **Health** or fitness records
- **Advertising identifiers** (IDFA) or any tracking identifiers
- **Analytics** or usage statistics
- **Crash reports** or diagnostic telemetry
- Any data used to **track you** across other apps or websites

---

## 3. How We Use Your Information

We use the limited information described above only to:

- **Run the App's core features** — schedule and ring your alarms and run wake-up missions.
- **Maintain your wake-up streak** on your device.
- **Back up and sync** your alarms and streak across your devices, if you sign in.
- **Authenticate you** and keep your account secure, if you sign in.
- **Unlock paid features** based on your Apple subscription status.
- **Respond to you** if you contact us for support or to exercise a privacy right.

We do **not** use your information for advertising, profiling, or automated decision-making, and we do **not** sell it.

---

## 4. How Your Information Is Shared

We do not sell your personal information and we do not share it for advertising. We share information only with the service providers strictly necessary to operate the App:

| Provider | Purpose | What they receive |
|---|---|---|
| **Google Firebase** (Authentication & Cloud Firestore), operated by Google LLC | Optional account sign-in and cloud backup/sync | Your account info (Section 2.2) and backed-up data (Section 2.3) — **only if you sign in** |
| **Google Sign-In**, operated by Google LLC | Sign you in if you choose Google | Authenticates you and returns a sign-in token — **only if you choose Google** |
| **Apple** (Sign in with Apple, App Store / StoreKit, AlarmKit) | Optional Apple sign-in, subscription processing, and alarm scheduling | Authentication and your subscription transaction — handled under Apple's privacy policy |

These providers process data on our behalf or as independent controllers under their own privacy policies:

- Google Privacy Policy: https://policies.google.com/privacy
- Firebase Privacy & Security: https://firebase.google.com/support/privacy
- Apple Privacy Policy: https://www.apple.com/legal/privacy/

We may also disclose information if **required by law**, such as to comply with a valid legal process, or to protect our rights, safety, or the safety of others. If the App is ever involved in a merger, acquisition, or sale of assets, we will require any successor to honor this Privacy Policy.

---

## 5. Data Storage, Security, and Retention

**Where your data lives.** Local data (alarms, streak, preferences) is stored on your device. If you sign in, your backed-up data and account information are stored in Google Firebase (Cloud Firestore and Firebase Authentication).

**Security.** Data sent to and from Firebase is encrypted in transit (HTTPS/TLS) and encrypted at rest by Google. Your cloud record is private to your account. However, no method of transmission over the Internet or method of electronic storage is 100% secure; while we strive to use commercially acceptable means to protect your information, we cannot guarantee its absolute security.

**Retention.**

- **On-device data** remains on your device until you delete it in the App or delete the App itself.
- **Cloud account and backup data** is retained for as long as your account exists. When you delete your account (see Section 6), this data is deleted.

---

## 6. Your Choices and Rights

You are in control of your data:

- **Use without an account.** You can use all core alarm features without ever signing in, keeping all data on your device.
- **Sign out.** Signing out stops further cloud backup.
- **Delete your account and cloud data.** In the App, go to **Settings → Delete account**. This permanently deletes your account and all of your backed-up alarms and streak data from the cloud (Firebase Authentication and Cloud Firestore). Alarms already on your device remain there until you delete the App.
- **Manage permissions.** You can grant or revoke Motion & Fitness and Notification permissions at any time in the iOS **Settings** app.
- **Manage your subscription.** Manage or cancel your subscription in the App Store (Settings → your name → Subscriptions).

To make any other request about your data, contact us at **inandha97@gmail.com** (see Section 10).

---

## 7. Your Rights Under the GDPR (EEA, UK & Switzerland)

If you are in the European Economic Area, the United Kingdom, or Switzerland, you have the following rights regarding your personal data:

- The right to **access** the personal data we hold about you.
- The right to **rectification** of inaccurate data.
- The right to **erasure** ("right to be forgotten").
- The right to **restrict** or **object** to processing.
- The right to **data portability**.
- The right to **withdraw consent** at any time, where processing is based on consent.
- The right to **lodge a complaint** with your local supervisory authority.

**Legal bases for processing.** We process your information under the following lawful bases: **performance of a contract** (to provide the App and its features you request, including backup when you sign in); **consent** (for example, when you choose to enable motion-based missions or sign in — which you may withdraw at any time); and our **legitimate interests** in operating, securing, and supporting the App, balanced against your rights.

**International transfers.** Our cloud provider (Google Firebase) may process and store data on servers located in the United States and other countries. Where data is transferred outside the EEA/UK, it is protected by appropriate safeguards such as the European Commission's Standard Contractual Clauses.

To exercise any of these rights, contact us at **inandha97@gmail.com**.

---

## 8. Your Rights Under the CCPA/CPRA (California)

If you are a California resident, you have the right to:

- **Know** what personal information we collect, use, and disclose (described throughout this Policy).
- **Access** a copy of the personal information we hold about you.
- **Delete** your personal information (see Section 6).
- **Correct** inaccurate personal information.
- **Opt out of the "sale" or "sharing"** of personal information.
- **Not be discriminated against** for exercising your privacy rights.

**We do not sell or share your personal information** as those terms are defined under the CCPA/CPRA, and we have not done so in the preceding 12 months. We do not knowingly sell or share the personal information of minors under 16.

The categories of personal information we may collect are **identifiers** (account ID, email, name) and **commerce information** (subscription status), collected only as described above. To exercise your California rights, contact us at **inandha97@gmail.com**. You may use an authorized agent to submit a request on your behalf.

---

## 9. Children's Privacy

So Alarmed is **not directed to children under the age of 13** (or the equivalent minimum age in your country, such as 16 in parts of the EEA), and we do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us at **inandha97@gmail.com** and we will delete it.

---

## 10. Apple App Store Privacy Disclosures

For transparency, this maps to Apple's App Privacy ("nutrition label") categories:

- **Data linked to you** (only if you sign in): **Contact Info** (name, email) and **Identifiers** (account ID), used for **App Functionality** (account backup and sync). Not used for tracking.
- **Data not linked to you:** **Purchases** (subscription status), used for App Functionality.
- **Data used to track you:** **None.**
- **Data not collected:** location, contacts, browsing/search history, health, sensitive info, usage/diagnostics, and advertising data. Motion data is used live and never collected or stored.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last updated" date at the top of this page and, for material changes, provide notice within the App where appropriate. Your continued use of the App after an update means you accept the revised Policy.

---

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact:

**Nandha Kumar Ilangovan**
Developer of So Alarmed
Email: **inandha97@gmail.com**

We will respond to legitimate requests within a reasonable timeframe and within any period required by applicable law.
