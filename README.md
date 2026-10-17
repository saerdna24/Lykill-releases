# Lykill

Ein Passwort-Manager für Mac und iPhone, der Ihre Daten bei Ihnen behält: Ende-zu-Ende-verschlüsselt,
mit einem Master-Passwort, das nie gespeichert oder übertragen wird.

> *Lykill* ist das isländische Wort für **Schlüssel**.

## Download

**[Neueste Version herunterladen](https://github.com/saerdna24/Lykill-releases/releases/latest)**

Laden Sie dort unter **Assets** die Datei **`Lykill-X.Y.Z.zip`** herunter. Die Einträge
„Source code“ fügt GitHub automatisch hinzu; sie enthalten nicht die App.

## Funktionen

- **Anmeldungen, Karten, Notizen, Identitäten** – jedes geheime Feld einzeln mit AES-256-GCM verschlüsselt
- **AutoFill** für Passwörter, Passkeys und Bestätigungscodes (TOTP) in Safari und anderen Apps
- **Entsperren mit Touch ID** oder der Apple Watch
- **Import** aus KeePass/KeePassXC und verschlüsselte Sicherungskopien
- **Synchronisation** über einen eigenen WebDAV-Server, z. B. ein NAS – der Server sieht nur verschlüsselte Daten

## Voraussetzungen

- **macOS 14** (Sonoma) oder neuer
- Läuft auf **Intel-Macs** und **Macs mit Apple Silicon**
- Ein **Zugangsschlüssel** – Lykill wird privat weitergegeben. Ohne Schlüssel öffnet sich ein
  vorhandener Tresor schreibgeschützt.

## Installation

1. Die ZIP-Datei herunterladen und öffnen (Doppelklick entpackt sie).
2. **Lykill** in den Ordner **Programme** ziehen.
3. Lykill starten und den Zugangsschlüssel einfügen.

Die App ist von Apple beglaubigt (notarisiert) und öffnet sich ohne Warnhinweis.

## Updates

Neue Versionen installiert Lykill selbst: **Lykill → Nach Updates suchen …** Die Updates sind signiert
und werden vor der Installation geprüft.

---

Dieses Repository enthält nur die fertigen Programmversionen und den Update-Feed, nicht den Quellcode.
