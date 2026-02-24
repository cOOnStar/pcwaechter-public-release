# PCWächter – Public Releases

Dieses Repository enthält ausschließlich veröffentlichte Installer-Artefakte für PCWächter.
Der Quellcode liegt im privaten Hauptrepository.

## Zweck dieses Repositories

- Öffentliche Bereitstellung von Installationsdateien
- Stabiler Download-Endpunkt für den Bootstrapper
- Historie aller veröffentlichten Versionen

## Schnellstart (für Anwender)

1. Öffne die Seite [Releases](../../releases)
2. Lade aus der neuesten Version eine der folgenden Dateien:
	- **PC_Wachter_installer.exe** (empfohlen, kleiner Bootstrapper mit Download/Update-Logik)
	- **PCWachterSetup.exe** (direktes Setup)
3. Starte die Datei und folge dem Installer

## Inhalte pro Release

Jede Version enthält in der Regel:

- `installer-manifest.json` – Metadaten für Bootstrapper und Downloadziele
- `PC_Wachter_installer.exe` – Bootstrapper
- `PCWachterSetup.exe` – eigentliche Setup-Datei

## Update- und Download-Prinzip

- Der Bootstrapper lädt das Manifest aus dem neuesten Release.
- Auf Basis des Manifests wird die passende Setup-Datei heruntergeladen und gestartet.
- Dadurch bleiben Downloads für Endnutzer klein und aktuell.

## Sicherheit

- Prüfsummen werden im Release geführt.
- Bei aktivierter Signierung sind Setup und Bootstrapper digital signiert.

## Hinweise

- In diesem Repository werden keine Quellcode-Änderungen gepflegt.
- Issues und Entwicklung laufen im privaten Hauptrepository.
