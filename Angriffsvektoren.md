## 🚨 Typische Angriffsvektoren

Hier findest du eine Übersicht der häufigsten Angriffsvektoren, die Angreifer in der Praxis nutzen, um in Systeme einzudringen oder Schaden anzurichten:

---

### ✅ Netzwerkbasierte Angriffe
- Offene Ports ohne Notwendigkeit
- Schwache oder Standard-Passwörter bei Netzwerkdiensten
- Schwachstellen in Protokollen (z. B. SMBv1, Telnet, SNMP)
- Man-in-the-Middle (MITM) durch ARP-Spoofing, DNS-Spoofing, LLMNR/NBT-NS-Poisoning
- Unverschlüsselte Kommunikation (HTTP, FTP, ungesicherte APIs)

---

### ✅ Webbasierte Angriffe
- SQL-Injection (SQLi)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Directory Traversal / Path Traversal
- Command Injection
- Schwache Authentifizierung (z. B. keine 2FA, schwache Passwörter)
- Öffentlich zugängliche Admin-Panels oder APIs

---

### ✅ Clientseitige Angriffe
- Phishing-E-Mails mit schädlichen Links oder Anhängen
- Malvertising (bösartige Werbung)
- Drive-by-Downloads auf kompromittierten Webseiten

---

### ✅ Social Engineering
- Phishing und Spear-Phishing
- Telefonische Angriffe (Vishing)
- Tailgating (mitgehen hinter autorisierten Personen)
- USB-Drop (präparierte USB-Sticks in Büros oder öffentlichen Orten platzieren)

---

### ✅ Cloud & API-Angriffe
- Fehlkonfigurationen in IAM (z. B. Overprivilege)
- Öffentlich zugängliche S3-Buckets oder Cloud-Container
- Hartcodierte Zugangsdaten in Repos oder Images
- Unsichere oder ungeschützte APIs (fehlende Authentifizierung, kein Ratenlimit)

---

### ✅ WLAN-Angriffe
- Evil-Twin-Access-Points (falsche WLANs zur Abfangen von Daten)
- Deauthentication-Attacken (Clients zwingen, sich neu zu verbinden)
- Angriffe auf schwache WPA/WEP-Verschlüsselungen
- Rogue Access Points (nicht autorisierte APs im Firmennetz)

---

### ✅ Systembasierte Angriffe
- Lokale Privilege Escalation durch falsch gesetzte Berechtigungen oder veraltete Software
- Unsichere Standardkonfigurationen direkt nach Installation
- Nicht gepatchte Software mit bekannten Schwachstellen (CVE)

---

### ✅ Passwortangriffe
- Brute-Force- und Wörterbuchangriffe
- Credential-Stuffing (Nutzung von Daten aus anderen Leaks)
- Pass-the-Hash oder Pass-the-Ticket in Windows-Umgebungen

---

### ✅ Physische Angriffe
- Manipulation von Geräten oder Netzwerkkabeln
- Zugang zu Serverräumen durch unzureichende physische Sicherheitsmaßnahmen

---
