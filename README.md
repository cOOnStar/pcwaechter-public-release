# PC Wächter – Offizielle Downloads

Dieses Repository enthält ausschließlich die öffentlichen Installer-Artefakte für **PC Wächter**.

## Download

1. Öffne [Releases](../../releases)
2. Nutze in der neuesten Version bevorzugt:
   - **PCWaechter_live_installer.exe**
     - Kleiner Downloader (empfohlen)
     - Lädt automatisch den aktuellen Offline-Installer
3. Alternative:
   - **PCWaechter_offline_installer.exe**
     - Vollständiger Installer für direkte Installation

## Enthaltene Dateien je Release

- **PCWaechter_live_installer.exe** – Downloader-Installer
- **PCWaechter_offline_installer.exe** – Vollständiger Installer
- **installer-manifest.json** – Update-Metadaten (Version, URLs, Hashwerte)

## Updates in der App

- PC Wächter installiert Updates im Hintergrund über einen separaten Worker.
- Die App bleibt dabei nutzerfreundlich und zeigt nur den relevanten Status.

## Sicherheit

- Downloads erfolgen ausschließlich über HTTPS.
- Integritätsprüfung erfolgt per SHA256 anhand des Manifests.
- Signierte Installer werden als verifizierter Herausgeber angezeigt.
