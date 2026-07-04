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

### 2.7 Sign in with Apple

If you register or sign in using the "Sign in with Apple" button, Apple Inc. transmits the following data to us after your explicit authorisation:

| Data | Source | Storage Location |
|---|---|---|
| Apple user identifier (stable, pseudonymous) | Apple | Supabase Auth (EU, Germany — Frankfurt) |
| Email address — your real address, or Apple's private relay address if you choose "Hide My Email" | Apple | Supabase Auth (EU, Germany — Frankfurt) |
| Display name — transmitted by Apple **only on your first sign-in**, and only if you choose to share it | Apple | Supabase Auth (EU, Germany — Frankfurt) |

**Hide My Email:** If you use Apple's "Hide My Email" feature, we only receive a random relay address (`…@privaterelay.appleid.com`). Emails we send there are forwarded to you by Apple; we never learn your real email address.

**What we do not import:** Your Apple profile photo is not transferred. You upload your profile photo separately and deliberately within the app. On any sign-in after the first, Apple transmits only the user identifier — not your name.

**Token processing:** The identity token (JWT) issued by Apple is processed exclusively for secure authentication via Supabase and is not used for any other purpose. It is stored server-side and is not accessible to us in plaintext.

**Consent:** Use of Sign in with Apple requires that you have actively clicked the "Sign in with Apple" button and explicitly accepted our Terms of Service and this Privacy Policy by ticking the corresponding checkboxes. No implied or pre-ticked consent takes place.

---

### 2.8 Reports and Moderation

To keep the community safe, you can report another user's profile, profile picture, or chat message (Report function). When you submit a report, we process:

| Data | Purpose |
|---|---|
| Your user ID (reporter) | Handling the report and preventing abuse of the report function |
| The reported user's ID and a reference to the reported content | Reviewing and acting on the report |
| Report category (harassment, spam, inappropriate content, impersonation, other) and your optional free-text description | Assessing the report |
| Status and moderation timestamps | Documenting the review decision |

Reports are reviewed by a human being (see Section 10). We do not disclose the reporter's identity to the reported user.

---

## 3. Purpose and Legal Basis

| Data | Purpose | Legal Basis |
|---|---|---|
| Email, name | Account management | Art. 6(1)(b) GDPR — contract |
| Profile photo, profile data | Display in network | Art. 6(1)(b) GDPR |
| Google Account ID, email (OAuth) | Authentication via Google account | Art. 6(1)(a) GDPR — consent |
| Apple user identifier, email (Sign in with Apple) | Authentication via Apple account | Art. 6(1)(a) GDPR — consent |
| GPS location | Real-time discovery (~100 m accuracy) | Art. 6(1)(a) GDPR — consent |
| Check-in | Availability signal to nearby users | Art. 6(1)(a) GDPR — consent |
| Chat messages | Direct communication | Art. 6(1)(b) GDPR |
| Push notifications | Activity alerts | Art. 6(1)(a) GDPR — consent |
| Analytics | Product improvement (anonymised) | Art. 6(1)(f) GDPR |
| User reports (reporter, reported user, reason, message) | Community safety, abuse prevention, enforcement of the Terms | Art. 6(1)(f) GDPR — legitimate interest |

---

## 4. Consent and Withdrawal

All data-intensive features require explicit in-app consent. You can withdraw at any time:
- **Location:** Settings → Location Sharing (clears stored coordinates immediately)
- **Push notifications:** Settings → Notifications
- **Chat notifications:** Settings → Chat Notifications
- **Google sign-in:** Settings → Delete Account (removes all enmaru data linked to your Google account; processing by Google LLC is governed by Google's own Privacy Policy)
- **Sign in with Apple:** Settings → Delete Account (removes all enmaru data linked to your Apple account; you can also stop sharing at any time under iOS Settings → your name → Sign in with Apple. Processing by Apple Inc. is governed by Apple's own Privacy Policy)

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

### Apple Inc. — Sign in with Apple

For the optional sign-in via Apple account (Sign in with Apple), **Apple Inc., One Apple Park Way, Cupertino, CA 95014, USA** acts as an independent data controller within the meaning of Art. 4(7) GDPR.

**Data flow:** When you tap "Sign in with Apple", Apple authenticates you (on Apple devices via the system dialog) and issues a signed identity token, which we verify via Supabase. Apple logs this authentication event in accordance with its own Privacy Policy. We receive only the data specified in Section 2.7. If you choose "Hide My Email", Apple additionally operates the private email relay through which our messages reach you.

**Third-country transfer:** The transfer of data to Apple servers in the United States is based on Standard Contractual Clauses pursuant to Art. 46(2)(c) GDPR. Apple Inc. is additionally certified under the EU-U.S. Data Privacy Framework.

**Optionality:** Use of Sign in with Apple is entirely voluntary. Registration and sign-in using only an email address and password is always available and results in no functional disadvantage.

- Apple Privacy Policy: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)
- Sign in with Apple & your privacy: [support.apple.com/102571](https://support.apple.com/102571)

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

### Cookie Consent Management — Real Cookie Banner (Website)

To manage the cookies and similar technologies used (tracking pixels, web beacons, etc.) and related consents, we use the consent tool "Real Cookie Banner". Details on how "Real Cookie Banner" works can be found at [https://devowl.io/rcb/data-processing/](https://devowl.io/rcb/data-processing/).

The legal basis for the processing of personal data in this context are Art. 6(1)(c) GDPR and Art. 6(1)(f) GDPR. Our legitimate interest is the management of the cookies and similar technologies used and the related consents.

The provision of personal data is neither contractually required nor necessary for the conclusion of a contract. You are not obliged to provide the personal data. If you do not provide the personal data, we will not be able to manage your consents.

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
- **Apple Sign-In data (Supabase Auth):** until account deletion; Apple processes data on its end in accordance with its own deletion policy
- **User reports:** retained while under review and, once resolved, for up to **12 months** for safety documentation and to detect repeat abuse (Art. 6(1)(f) GDPR), then deleted
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
