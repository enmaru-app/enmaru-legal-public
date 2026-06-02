# Cookie- und Speicher-Richtlinie

**Stand:** 29. Mai 2026
**Verantwortlicher:** Sebastian Hesse, Winsstr. 61, 10405 Berlin — [privacy@enmaru.app](mailto:privacy@enmaru.app)

---

## 1. Überblick

enmaru ist eine native Mobile-App und verwendet **keine klassischen Browser-Cookies**. Stattdessen nutzen wir geräteseitige Speichermechanismen, die nachfolgend vollständig beschrieben sind.

---

## 2. Gerätespeicher

### Capacitor Preferences (NSUserDefaults / SharedPreferences)
- **Was:** App-Einstellungen, Sprachpräferenz, Sitzungsdaten, Chat-Cache
- **Zweck:** Schnelle lokale Datenvorhaltung ohne Server-Roundtrip
- **Speicherdauer:** Bis zur Abmeldung oder App-Deinstallation
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung)

### Supabase Auth-Token
- **Was:** JWT-Authentifizierungstoken für die aktive Sitzung
- **Zweck:** Eingeloggt bleiben ohne erneute Passworteingabe
- **Speicherdauer:** Bis zur Abmeldung
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO

---

## 3. Drittanbieter-SDKs (geräteseitig)

### OneSignal (Push-Benachrichtigungen)
- **Was:** Geräte-Token zur Zustellung von Push-Nachrichten
- **Zweck:** Benachrichtigungen bei neuen Nachrichten
- **Aktivierung:** Nur nach expliziter Einwilligung in der App
- **Widerruf:** Einstellungen → Notifications → Deaktivieren
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO (Einwilligung)

---

## 4. Analytics

- Die App erfasst anonymisierte Nutzungsereignisse (z. B. welche Features genutzt werden)
- **Kein Rückschluss auf einzelne Personen möglich**
- Keine Weitergabe an Werbenetzwerke oder Dritte
- Speicherung ausschließlich auf unseren Servern (Supabase, EU Irland)
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an Produktverbesserung)

---

## 5. Was wir NICHT nutzen

- ❌ Keine Tracking-Cookies
- ❌ Keine Werbe-Cookies
- ❌ Kein Google Analytics, Facebook Pixel oder ähnliche Tracking-Dienste
- ❌ Kein Cross-Site-Tracking
- ❌ Keine Weitergabe von Gerätedaten an Werbetreibende

---

## 6. Löschen gespeicherter Daten

Du kannst alle lokal gespeicherten Daten löschen durch:
- **Abmelden** in der App (löscht Session-Token)
- **Account löschen** unter Einstellungen (löscht alle Daten inkl. Server-Daten)
- **App deinstallieren** (löscht alle lokalen Daten)

---

## 7. Änderungen

Wesentliche Änderungen werden registrierten Nutzern mitgeteilt.
