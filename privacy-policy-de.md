# Datenschutzerklärung

**Stand:** 30. Mai 2026
**Verantwortlicher:** Sebastian Hesse, Winsstr. 61, 10405 Berlin — [privacy@enmaru.app](mailto:privacy@enmaru.app)
**Impressum:** In der App unter Einstellungen → Support & Legal → Impressum

---

## 1. Geltungsbereich

Diese Datenschutzerklärung gilt für die Nutzung der enmaru (iOS und Android) sowie aller damit verbundenen Dienste. Die App richtet sich ausschließlich an Personen ab 18 Jahren. Wir erheben wissentlich keine personenbezogenen Daten von Personen unter 18 Jahren.

---

## 2. Erhobene Daten

### 2.1 Registrierung
- E-Mail-Adresse, Passwort (verschlüsselt), Einwilligungs-Zeitstempel
- Alternativ: Registrierung und Anmeldung per Google-Konto (Google OAuth 2.0) — siehe Abschnitt 2.6 und Abschnitt 5

### 2.2 Profilerstellung
- Vor- und Nachname (Pflicht), Profilfoto (Pflicht)
- Beruf, Unternehmen, Branche, Interessen, Kontaktdaten (freiwillig)

### 2.3 App-Nutzung
- GPS-Standort (nur mit Einwilligung, nur bei aktivem Refresh)
- Check-in-Standort (Venue-Name + Adresse, nur nach Bestätigung)
- Chat-Nachrichten
- App-Nutzungsereignisse (anonymisiert, kein Personenbezug möglich — siehe Abschnitt 6)

### 2.4 Gerätezugriffsrechte

Die App benötigt folgende Gerätezugriffsrechte:

| Zugriffsrecht | Zweck | Aktivierung |
|---|---|---|
| Standort (GPS) | Entfernung zu anderen Nutzern berechnen | Nur nach expliziter Einwilligung in der App |
| Fotobibliothek / Kamera | Profilfoto hochladen | Nur auf Anforderung beim Fotoauswahl-Dialog |
| Push-Benachrichtigungen | Hinweise auf neue Nachrichten | Nur nach expliziter Einwilligung in der App |

Alle Zugriffsrechte können jederzeit in den Systemeinstellungen des Geräts widerrufen werden.

### 2.5 Einwilligungen (mit Zeitstempel)
- AGB und Datenschutz, GPS-Standort, Push-Benachrichtigungen, Chat-Benachrichtigungen

### 2.6 Google-Authentifizierung (OAuth 2.0)

Wenn du dich über die Schaltfläche „Mit Google anmelden" registrierst oder anmeldest, übermittelt Google LLC nach deiner Freigabe folgende Daten an uns:

| Datum | Herkunft | Speicherort |
|---|---|---|
| E-Mail-Adresse deines Google-Kontos | Google | Supabase Auth (EU, Irland) |
| Google Account ID (pseudonymisierter Bezeichner) | Google | Supabase Auth (EU, Irland) |
| Anzeigename deines Google-Kontos | Google | Supabase Auth (EU, Irland) |

**Was wir nicht übernehmen:** Dein Google-Profilfoto wird nicht automatisch importiert. Du lädst dein Profilfoto separat und bewusst innerhalb der App hoch.

**Token-Verarbeitung:** Das von Google ausgestellte OAuth-Token wird ausschließlich zur sicheren Authentifizierung über Supabase (PKCE-Verfahren, RFC 7636) verarbeitet und nicht für andere Zwecke genutzt. Es wird serverseitig gespeichert und ist für uns nicht im Klartext zugänglich.

**Einwilligung:** Die Nutzung von Google OAuth setzt voraus, dass du zuvor aktiv die Schaltfläche „Mit Google anmelden" betätigt sowie unsere AGB und diese Datenschutzerklärung per Checkbox ausdrücklich akzeptiert hast. Eine stillschweigende oder voreingestellte Einwilligung findet nicht statt.

---

### 2.7 Anmeldung mit Apple (Sign in with Apple)

Wenn du dich über die Schaltfläche „Mit Apple anmelden" registrierst oder anmeldest, übermittelt Apple Inc. nach deiner Freigabe folgende Daten an uns:

| Datum | Herkunft | Speicherort |
|---|---|---|
| Apple-Nutzerkennung (stabil, pseudonymisiert) | Apple | Supabase Auth (EU, Irland) |
| E-Mail-Adresse — deine echte Adresse oder Apples anonyme Weiterleitungs&shy;adresse, falls du „E-Mail-Adresse verbergen" wählst | Apple | Supabase Auth (EU, Irland) |
| Anzeigename — von Apple **nur bei der ersten Anmeldung** übermittelt, und nur wenn du dem zustimmst | Apple | Supabase Auth (EU, Irland) |

**E-Mail-Adresse verbergen:** Wenn du Apples Funktion „E-Mail-Adresse verbergen" nutzt, erhalten wir nur eine zufällige Weiterleitungsadresse (`…@privaterelay.appleid.com`). E-Mails, die wir dorthin senden, werden dir von Apple zugestellt; deine echte E-Mail-Adresse erfahren wir nicht.

**Was wir nicht übernehmen:** Dein Apple-Profilfoto wird nicht übernommen. Du lädst dein Profilfoto separat und bewusst innerhalb der App hoch. Bei jeder Anmeldung nach der ersten übermittelt Apple ausschließlich die Nutzerkennung — nicht deinen Namen.

**Token-Verarbeitung:** Das von Apple ausgestellte Identity-Token (JWT) wird ausschließlich zur sicheren Authentifizierung über Supabase verarbeitet und nicht für andere Zwecke genutzt. Es wird serverseitig gespeichert und ist für uns nicht im Klartext zugänglich.

**Einwilligung:** Die Nutzung von „Mit Apple anmelden" setzt voraus, dass du zuvor aktiv die Schaltfläche betätigt sowie unsere AGB und diese Datenschutzerklärung per Checkbox ausdrücklich akzeptiert hast. Eine stillschweigende oder voreingestellte Einwilligung findet nicht statt.

---

### 2.8 Meldungen und Moderation

Zum Schutz der Community kannst du das Profil, das Profilbild oder eine Chat-Nachricht eines anderen Nutzers melden (Melde-Funktion). Wenn du eine Meldung absendest, verarbeiten wir:

| Daten | Zweck |
|---|---|
| Deine Nutzer-ID (meldende Person) | Bearbeitung der Meldung, Verhinderung von Missbrauch der Melde-Funktion |
| ID des gemeldeten Nutzers und Verweis auf den gemeldeten Inhalt | Prüfung und Bearbeitung der Meldung |
| Meldegrund (Belästigung, Spam, unangemessener Inhalt, Identitätsmissbrauch, Sonstiges) und deine optionale Freitext-Beschreibung | Bewertung der Meldung |
| Status und Moderations-Zeitstempel | Dokumentation der Prüfentscheidung |

Meldungen werden durch einen Menschen geprüft (siehe Abschnitt 10). Die Identität der meldenden Person wird dem gemeldeten Nutzer nicht offengelegt.

---

## 3. Zweck und Rechtsgrundlage

| Daten | Zweck | Rechtsgrundlage |
|---|---|---|
| E-Mail, Name | Account-Verwaltung | Art. 6 Abs. 1 lit. b DSGVO |
| Profilfoto, Profildaten | Darstellung im Netzwerk | Art. 6 Abs. 1 lit. b DSGVO |
| Google Account ID, E-Mail (OAuth) | Authentifizierung via Google-Konto | Art. 6 Abs. 1 lit. a DSGVO |
| Apple-Nutzerkennung, E-Mail (Anmeldung mit Apple) | Authentifizierung via Apple-Konto | Art. 6 Abs. 1 lit. a DSGVO |
| GPS-Standort | Echtzeit-Discovery (~100 m Genauigkeit) | Art. 6 Abs. 1 lit. a DSGVO |
| Check-in | Verfügbarkeitsanzeige für Nutzer im Umkreis | Art. 6 Abs. 1 lit. a DSGVO |
| Chat-Nachrichten | Direkte Kommunikation | Art. 6 Abs. 1 lit. b DSGVO |
| Push-Benach&shy;richtigungen | Hinweise auf Aktivitäten | Art. 6 Abs. 1 lit. a DSGVO |
| Analytics | Produktverbesserung (anonymisiert) | Art. 6 Abs. 1 lit. f DSGVO |
| Nutzer-Meldungen (meldende Person, gemeldeter Nutzer, Grund, Nachricht) | Sicherheit der Community, Missbrauchs&shy;prävention, Durchsetzung der AGB | Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse |

---

## 4. Einwilligungen und Widerruf

Alle datenintensiven Funktionen erfordern eine explizite In-App-Einwilligung. Widerruf jederzeit über:
- **Standort:** Einstellungen → Location Sharing (löscht gespeicherte Koordinaten sofort)
- **Push:** Einstellungen → Notifications
- **Chat-Benachrichtigungen:** Einstellungen → Chat Notifications
- **Google-Verknüpfung:** Einstellungen → Account löschen (entfernt alle mit deinem Google-Konto verknüpften Daten aus der enmaru; die Verarbeitung durch Google LLC richtet sich nach deren Datenschutzrichtlinie)
- **Anmeldung mit Apple:** Einstellungen → Account löschen (entfernt alle mit deinem Apple-Konto verknüpften Daten aus der enmaru; du kannst die Verknüpfung zudem jederzeit unter iOS-Einstellungen → dein Name → Mit Apple anmelden widerrufen. Die Verarbeitung durch Apple Inc. richtet sich nach deren Datenschutzrichtlinie)

---

## 5. Drittanbieter

### App-Stores (Apple / Google)

Beim Download der App über den **Apple App Store** bzw. **Google Play Store** werden personenbezogene Daten (z. B. Apple-ID/Google-Konto, Gerätekennung, IP-Adresse, Zeitpunkt des Downloads) durch Apple Inc. bzw. Google LLC als eigenständig Verantwortliche verarbeitet. Auf diese Verarbeitung haben wir keinen Einfluss.

- Apple Datenschutz: [apple.com/de/privacy/](https://www.apple.com/de/privacy/)
- Google Datenschutz: [policies.google.com/privacy](https://policies.google.com/privacy)

### Google LLC — OAuth-Authentifizierung

Für die optional nutzbare Anmeldung per Google-Konto (Google Sign-In / OAuth 2.0) ist **Google LLC, 1600 Amphitheatre Parkway, Mountain View, CA 94043, USA**, als eigenständig Verantwortlicher im Sinne des Art. 4 Nr. 7 DSGVO tätig.

**Datenfluss:** Beim Klick auf „Mit Google anmelden" wird dein Browser/Gerät zur Google-Authentifizierungsseite weitergeleitet. Google protokolliert diese Anfrage sowie deinen Anmeldevorgang gemäß seiner eigenen Datenschutzrichtlinie. Anschließend übermittelt Google uns einen verschlüsselten Autorisierungscode (PKCE-Verfahren), den wir gegen ein Zugriffstoken austauschen. Dabei erhalten wir ausschließlich die in Abschnitt 2.6 genannten Daten.

**Drittlandtransfer:** Die Übermittlung von Daten an Google-Server in den USA erfolgt auf Basis von Standardvertragsklauseln gemäß Art. 46 Abs. 2 lit. c DSGVO. Google LLC ist darüber hinaus dem EU-U.S. Data Privacy Framework (Beschluss der EU-Kommission vom 10. Juli 2023) beigetreten.

**Optionalität:** Die Nutzung von Google OAuth ist vollständig freiwillig. Eine Registrierung und Anmeldung ausschließlich per E-Mail-Adresse und Passwort ist jederzeit möglich und führt zu keinen funktionalen Nachteilen.

- Google-Datenschutzrichtlinie: [policies.google.com/privacy](https://policies.google.com/privacy)
- Google-Nutzungsbedingungen: [policies.google.com/terms](https://policies.google.com/terms)

### Apple Inc. — Anmeldung mit Apple

Für die optional nutzbare Anmeldung per Apple-Konto („Mit Apple anmelden") ist **Apple Inc., One Apple Park Way, Cupertino, CA 95014, USA**, als eigenständig Verantwortlicher im Sinne des Art. 4 Nr. 7 DSGVO tätig.

**Datenfluss:** Beim Tippen auf „Mit Apple anmelden" authentifiziert Apple dich (auf Apple-Geräten über den System-Dialog) und stellt ein signiertes Identity-Token aus, das wir über Supabase verifizieren. Apple protokolliert diesen Anmeldevorgang gemäß seiner eigenen Datenschutzrichtlinie. Wir erhalten ausschließlich die in Abschnitt 2.7 genannten Daten. Wählst du „E-Mail-Adresse verbergen", betreibt Apple zusätzlich den anonymen E-Mail-Weiterleitungsdienst, über den unsere Nachrichten dich erreichen.

**Drittlandtransfer:** Die Übermittlung von Daten an Apple-Server in den USA erfolgt auf Basis von Standardvertragsklauseln gemäß Art. 46 Abs. 2 lit. c DSGVO. Apple Inc. ist darüber hinaus unter dem EU-U.S. Data Privacy Framework zertifiziert.

**Optionalität:** Die Nutzung von „Mit Apple anmelden" ist vollständig freiwillig. Eine Registrierung und Anmeldung ausschließlich per E-Mail-Adresse und Passwort ist jederzeit möglich und führt zu keinen funktionalen Nachteilen.

- Apple Datenschutzrichtlinie: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)
- Anmelden mit Apple & Datenschutz: [support.apple.com/de-de/102571](https://support.apple.com/de-de/102571)

### Supabase
- Hosting: EU (Deutschland, AWS eu-central-1 (Frankfurt)) · [supabase.com/privacy](https://supabase.com/privacy)

### OneSignal (Push)
- Hosting: EU (Niederlande, Google Cloud) · kein Drittlandtransfer
- [onesignal.com/privacy_policy](https://onesignal.com/privacy_policy)

### Google Maps Platform (Venue-Suche)
- Rechtsbeziehung: unabhängiger Verantwortlicher (Controller-Controller)
- API-Aufrufe erfolgen ausschließlich über unsere Server — deine IP wird Google nicht übermittelt
- [mapsplatform.google.com/resources/trust-center/gdpr/](https://mapsplatform.google.com/resources/trust-center/gdpr/)

### GitHub, Inc. (Feedback-Einreichungen)
- **GitHub, Inc.** (Microsoft-Tochter), 88 Colin P Kelly Jr St, San Francisco, CA 94107, USA
- **Funktion:** Wenn du freiwillig In-App-Feedback einreichst (Einstellungen → Feedback), wird dein Feedback als Issue in unser privates GitHub-Repository übermittelt. GitHub handelt dabei als unser Auftragsverarbeiter.
- **Verarbeitete Daten:** Dein Feedback-Text, Geräteinformationen (Plattform, OS-Version, Gerätemodell, App-Version), aktueller Bildschirm sowie eine pseudonymisierte Nutzer-ID (erste 8 Zeichen deiner Konto-ID — nicht auf deine Identität zurückführbar). Es werden keine Namen, E-Mail-Adressen oder genauen Standortdaten übermittelt.
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO — ausdrückliche Einwilligung (freiwillige, nutzerinitiierte Aktion)
- **Freiwilligkeit:** Vollständig freiwillig — du bist zu keiner Zeit verpflichtet, Feedback einzureichen
- **Drittlandtransfer:** GitHub Inc. ist in den USA ansässig; Grundlage: EU-Standardvertragsklauseln
- **Datenschutzerklärung:** [docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
- **Aufbewahrung:** Feedback-Issues werden in unserem privaten Repository gespeichert und können von uns jederzeit gelöscht werden

### IONOS (DNS, Hosting & Transaktions-E-Mail)
- Hosting: Deutschland (EU) · AVV automatisch über AGB eingeschlossen

### Cookie-Einwilligungsverwaltung — Real Cookie Banner (Website)

Zur Verwaltung der eingesetzten Cookies und ähnlichen Technologien (Tracking-Pixel, Web-Beacons etc.) und diesbezüglicher Einwilligungen setzen wir das Consent-Tool „Real Cookie Banner" ein. Details zur Funktionsweise von „Real Cookie Banner" findest du unter [https://devowl.io/de/rcb/datenverarbeitung/](https://devowl.io/de/rcb/datenverarbeitung/).

Rechtsgrundlagen für die Verarbeitung der personenbezogenen Daten in diesem Zusammenhang sind Art. 6 Abs. 1 lit. c DSGVO und Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse ist die Verwaltung der eingesetzten Cookies und ähnlichen Technologien und der diesbezüglichen Einwilligungen.

Die Bereitstellung der personenbezogenen Daten ist weder vertraglich vorgeschrieben noch für den Abschluss eines Vertrages notwendig. Du bist nicht verpflichtet, die personenbezogenen Daten bereitzustellen. Wenn du die personenbezogenen Daten nicht bereitstellst, können wir deine Einwilligungen nicht verwalten.

---

## 6. Analytics

Wir betreiben ein **selbst gehostetes, serverseitiges** Analysesystem auf Basis von Supabase (EU Irland). Dabei werden ausschließlich anonymisierte App-Nutzungsereignisse erfasst (z. B. welche Funktionen aufgerufen werden). Es werden **keine** Geräte-IDs, IP-Adressen, Standortdaten oder sonstige personenbezogene Daten für Analytics-Zwecke verarbeitet. Ein Rückschluss auf einzelne Personen ist technisch ausgeschlossen. Daten werden nicht an Dritte weitergegeben und nicht für Werbezwecke genutzt.

---

## 7. Standortdaten

- Exakter Standort wird niemals anderen Nutzern übermittelt
- Angezeigt wird ausschließlich eine gerundete Entfernung (~100 m Schritte)
- Check-in: Venue-Name und Verfügbarkeit sichtbar für Nutzer im Umkreis — du wirst vor jedem Check-in ausdrücklich informiert

---

## 8. Speicherdauer

- **Chat-Nachrichten:** werden **1 Jahr** nach dem Sendedatum automatisch gelöscht (Art. 5 Abs. 1 lit. c DSGVO — Datensparsamkeit). Dies gilt unabhängig davon, ob das Konto noch aktiv ist.
- **Operative Daten (Profil, Standort, Events):** bis zur Kontolöschung
- **Google-OAuth-Daten (Supabase Auth):** bis zur Kontolöschung; Google verarbeitet Daten auf seiner Seite nach seiner eigenen Löschrichtlinie
- **Apple-Anmeldedaten (Supabase Auth):** bis zur Kontolöschung; Apple verarbeitet Daten auf seiner Seite nach seiner eigenen Löschrichtlinie
- **Nutzer-Meldungen:** während der Prüfung sowie nach Abschluss für bis zu **12 Monate** zur Sicherheitsdokumentation und zur Erkennung wiederholten Missbrauchs (Art. 6 Abs. 1 lit. f DSGVO), danach Löschung
- **Compliance-Daten (nach Löschung):** anonymisierter Nachweis für max. 3 Jahre (Art. 5 Abs. 2, Art. 17 Abs. 3 DSGVO), danach automatisch gelöscht

---

## 9. Deine Rechte

- **Auskunft** (Art. 15) — [privacy@enmaru.app](mailto:privacy@enmaru.app)
- **Berichtigung** (Art. 16) — direkt in der App
- **Löschung** (Art. 17) — Einstellungen → Account löschen
- **Einschränkung** (Art. 18) — [privacy@enmaru.app](mailto:privacy@enmaru.app)
- **Datenübertragbarkeit** (Art. 20) — Einstellungen → Support & Legal → Download my data. Du erhältst einen **sicheren Download-Link per E-Mail** (gültig 24 Stunden, max. 3 Anfragen pro 24 Stunden). Die Datei wird nach Ablauf automatisch gelöscht. Keine personenbezogenen Daten im E-Mail-Anhang.
- **Widerspruch** (Art. 21) — Location Sharing Toggle
- **Widerruf** (Art. 7 Abs. 3) — jederzeit über die Toggles in den Einstellungen

---

## 10. Beschwerderecht

**Berliner Beauftragte für Datenschutz und Informationsfreiheit**
Friedrichstr. 219, 10969 Berlin · [mailbox@datenschutz-berlin.de](mailto:mailbox@datenschutz-berlin.de)
[datenschutz-berlin.de](https://www.datenschutz-berlin.de)

---

## 11. Änderungen

Wesentliche Änderungen werden registrierten Nutzern mitgeteilt.
