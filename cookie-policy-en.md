# Cookie and Storage Policy

**Last updated:** 29 May 2026
**Controller:** Sebastian Hesse, Winsstr. 61, 10405 Berlin, Germany — [privacy@enmaru.app](mailto:privacy@enmaru.app)

---

## 1. Overview

enmaru is a native mobile app and does **not use traditional browser cookies**. Instead, we use on-device storage mechanisms, which are fully described below.

---

## 2. On-Device Storage

### Capacitor Preferences (NSUserDefaults / SharedPreferences)
- **What:** App settings, language preference, session data, chat cache
- **Purpose:** Fast local data access without server round-trips
- **Duration:** Until sign-out or app uninstall
- **Legal basis:** Art. 6(1)(b) GDPR — contract performance

### Supabase Auth Token
- **What:** JWT authentication token for the active session
- **Purpose:** Stay signed in without re-entering your password
- **Duration:** Until sign-out
- **Legal basis:** Art. 6(1)(b) GDPR

---

## 3. Third-Party SDKs (On-Device)

### OneSignal (Push Notifications)
- **What:** Device token for push notification delivery
- **Purpose:** Notifications for new messages
- **Activation:** Only after explicit in-app consent
- **Withdrawal:** Settings → Notifications → Disable
- **Legal basis:** Art. 6(1)(a) GDPR — consent

---

## 4. Analytics

- The app captures anonymised usage events (e.g. which features are used)
- **No identification of individual users is possible**
- No sharing with advertising networks or third parties
- Stored exclusively on our servers (Supabase, EU Ireland)
- **Legal basis:** Art. 6(1)(f) GDPR — legitimate interest in product improvement

---

## 5. What We Do NOT Use

- ❌ No tracking cookies
- ❌ No advertising cookies
- ❌ No Google Analytics, Facebook Pixel or similar tracking services
- ❌ No cross-site tracking
- ❌ No sharing of device data with advertisers

---

## 6. Deleting Stored Data

You can delete all locally stored data by:
- **Signing out** in the app (deletes session token)
- **Deleting your account** in Settings (deletes all data including server-side data)
- **Uninstalling the app** (deletes all local data)

---

## 7. Changes

Material changes will be communicated to registered users.
