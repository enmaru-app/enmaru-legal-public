# Privacy Policy

**Last updated:** 30 May 2026
**Controller:** Sebastian Hesse, Winsstr. 61, 10405 Berlin, Germany — [privacy@enmaru.app](mailto:privacy@enmaru.app)

---

## 1. Scope

This Privacy Policy applies to the use of the enmaru (iOS and Android) and all related services. The app is intended exclusively for persons aged 18 and over. We do not knowingly collect personal data from persons under the age of 18.

---

## 2. Data We Collect

### 2.1 Registration
- Email address, password (hashed), consent timestamps
- Alternatively: registration and sign-in via Google account (Google OAuth 2.0) — see Sections 2.6 and 5

### 2.2 Profile Setup
- First and last name (required), profile photo (required)
- Profession, company, industry, interests, contact details (optional)

### 2.3 App Usage
- GPS coordinates (only with your consent, only on explicit refresh)
- Check-in location (venue name + address, only after confirmation)
- Chat messages, anonymised analytics events

### 2.4 Device Permissions

The app requires the following device permissions:

| Permission | Purpose | Activation |
|---|---|---|
| Location (GPS) | Calculate distance to other users | Only after explicit in-app consent |
| Photo Library / Camera | Upload profile photo | Only when requested via photo picker |
| Push Notifications | Alerts for new messages | Only after explicit in-app consent |

All permissions can be revoked at any time via your device's system settings.

### 2.5 Consents (stored with timestamp)
- Terms & Privacy, GPS location, push notifications, chat notifications

### 2.6 Google Sign-In (OAuth 2.0)

If you register or sign in using the "Continue with Google" button, Google LLC transmits the following data to us after your explicit authorisation:

| Data | Source | Storage Location |
|---|---|---|
| Email address of your Google account | Google | Supabase Auth (EU, Germany — Frankfurt) |
| Google Account ID (pseudonymous identifier) | Google | Supabase Auth (EU, Germany — Frankfurt) |
| Display name of your Google account | Google | Supabase Auth (EU, Germany — Frankfurt) |

**What we do not import:** Your Google profile photo is not automatically transferred. You upload your profile photo separately and deliberately within the app.

**Token processing:** The OAuth token issued by Google is processed exclusively for secure authentication via Supabase (PKCE flow, RFC 7636) and is not used for any other purpose. It is stored server-side and is not accessible to us in plaintext.

**Consent:** Use of Google OAuth requires that you have actively clicked the "Continue with Google" button and explicitly accepted our Terms of Service and this Privacy Policy by ticking the corresponding checkboxes. No implied or pre-ticked consent takes place.

---

## 3. Purpose and Legal Basis

| Data | Purpose | Legal Basis |
|---|---|---|
| Email, name | Account management | Art. 6(1)(b) GDPR — contract |
| Profile photo, profile data | Display in network | Art. 6(1)(b) GDPR |
| Google Account ID, email (OAuth) | Authentication via Google account | Art. 6(1)(a) GDPR — consent |
| GPS location | Real-time discovery (~100 m accuracy) | Art. 6(1)(a) GDPR — consent |
| Check-in | Availability signal to nearby users | Art. 6(1)(a) GDPR — consent |
| Chat messages | Direct communication | Art. 6(1)(b) GDPR |
| Push notifications | Activity alerts | Art. 6(1)(a) GDPR — consent |
| Analytics | Product improvement (anonymised) | Art. 6(1)(f) GDPR |

---

## 4. Consent and Withdrawal

All data-intensive features require explicit in-app consent. You can withdraw at any time:
- **Location:** Settings → Location Sharing (clears stored coordinates immediately)
- **Push notifications:** Settings → Notifications
- **Chat notifications:** Settings → Chat Notifications
- **Google sign-in:** Settings → Delete Account (removes all enmaru data linked to your Google account; processing by Google LLC is governed by Google's own Privacy Policy)

---

## 5. Third-Party Providers

### App Stores (Apple / Google)

When downloading the app via the **Apple App Store** or **Google Play Store**, personal data (e.g. Apple ID/Google account, device identifier, IP address, download timestamp) is processed by Apple Inc. and Google LLC respectively as independent controllers. We have no influence over this processing.

- Apple Privacy: [apple.com/privacy/](https://www.apple.com/privacy/)
- Google Privacy: [policies.google.com/privacy](https://policies.google.com/privacy)

### Google LLC — OAuth Authentication

For the optional sign-in via Google account (Google Sign-In / OAuth 2.0), **Google LLC, 1600 Amphitheatre Parkway, Mountain View, CA 94043, USA** acts as an independent data controller within the meaning of Art. 4(7) GDPR.

**Data flow:** When you click "Continue with Google", your browser/device is redirected to Google's authentication page. Google logs this request and your sign-in event in accordance with its own Privacy Policy. Google then transmits an encrypted authorisation code (PKCE flow) to us, which we exchange for an access token. In doing so, we receive only the data specified in Section 2.6.

**Third-country transfer:** The transfer of data to Google servers in the United States is based on Standard Contractual Clauses pursuant to Art. 46(2)(c) GDPR. Google LLC is additionally a participant of the EU-U.S. Data Privacy Framework (European Commission adequacy decision of 10 July 2023).

**Optionality:** Use of Google OAuth is entirely voluntary. Registration and sign-in using only an email address and password is always available and results in no functional disadvantage.

- Google Privacy Policy: [policies.google.com/privacy](https://policies.google.com/privacy)
- Google Terms of Service: [policies.google.com/terms](https://policies.google.com/terms)

### Supabase
- Hosting: EU (Germany, AWS eu-central-1, Frankfurt) · [supabase.com/privacy](https://supabase.com/privacy)

### OneSignal (Push Notifications)
- Hosting: EU (Netherlands, Google Cloud) · no third-country transfer
- [onesignal.com/privacy_policy](https://onesignal.com/privacy_policy)

### Google Maps Platform (Venue Search)
- Legal relationship: independent Data Controller (Controller-Controller)
- All API calls are server-side — your IP address is never transmitted to Google
- [mapsplatform.google.com/resources/trust-center/gdpr/](https://mapsplatform.google.com/resources/trust-center/gdpr/)

### GitHub, Inc. (Feedback Submissions)
- **GitHub, Inc.** (a Microsoft subsidiary), 88 Colin P Kelly Jr St, San Francisco, CA 94107, USA
- **Function:** When you voluntarily submit in-app feedback (Settings → Feedback), your feedback is sent to our private GitHub repository as an issue. GitHub acts as our processor.
- **Data processed:** Your feedback text, device information (platform, OS version, device model, app version), current screen, and a pseudonymised partial user ID (first 8 characters of your account ID — not reversible to your identity without additional data). No name, email address, or exact location is transmitted.
- **Legal basis:** Art. 6(1)(a) GDPR — explicit consent (voluntary, user-initiated action)
- **Optionality:** Entirely optional — you are never required to submit feedback
- **Third-country transfer:** GitHub Inc. is US-based; transfer basis: EU Standard Contractual Clauses
- **Privacy Policy:** [docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
- **Retention:** Feedback issues are stored in our private repository and may be deleted at any time by us

### IONOS (DNS, Hosting & Transactional Email)
- Hosting: Germany (EU) · DPA auto-incorporated via Terms of Service

---

## 6. Location Data

- Your exact location is never transmitted to other users
- Other users only see a rounded distance (~100 m increments)
- Check-ins are voluntary; you are explicitly informed before each check-in

---

## 7. Retention Periods

- **Chat messages:** automatically deleted after **1 year** from the date sent (Art. 5(1)(c) GDPR — data minimisation). This applies to all messages regardless of whether the account is active.
- **Operational data (profile, location, events):** until account deletion
- **Google OAuth data (Supabase Auth):** until account deletion; Google processes data on its end in accordance with its own deletion policy
- **Compliance records (post-deletion):** anonymised consent evidence for up to 3 years (Art. 5(2), Art. 17(3) GDPR), then automatically deleted

---

## 8. Your Rights

- **Access** (Art. 15) — [privacy@enmaru.app](mailto:privacy@enmaru.app)
- **Rectification** (Art. 16) — directly in the app
- **Erasure** (Art. 17) — Settings → Delete Account
- **Restriction** (Art. 18) — [privacy@enmaru.app](mailto:privacy@enmaru.app)
- **Data portability** (Art. 20) — Settings → Support & Legal → Download my data. You receive a **secure download link by email** (valid 24 hours, max. 3 requests per 24 hours). The file is automatically deleted after expiry. No personal data in the email attachment.
- **Object** (Art. 21) — Location Sharing toggle
- **Withdraw consent** (Art. 7(3)) — per-feature toggles in Settings

---

## 9. Right to Lodge a Complaint

**Berliner Beauftragte für Datenschutz und Informationsfreiheit (BlnBDI)**
Friedrichstr. 219, 10969 Berlin, Germany · [mailbox@datenschutz-berlin.de](mailto:mailbox@datenschutz-berlin.de)
[datenschutz-berlin.de](https://www.datenschutz-berlin.de)

---

## 10. Automated Decision-Making and Profiling

Pursuant to Art. 13(2)(f) GDPR, we hereby inform you:

**No automated decision-making, including profiling within the meaning of Art. 22(1) and (4) GDPR, takes place.** All decisions that have legal effect on users or similarly significantly affect them are made exclusively by human beings.

Note: The app calculates distances between users based on GPS coordinates. This constitutes a purely technical calculation without any evaluation, classification, or legal effect on the data subject.

---

## 11. Changes

Material changes will be communicated to registered users.
