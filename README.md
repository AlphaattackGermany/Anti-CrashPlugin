````markdown
# Anti-CrashPlugin - CrashGuard

Dieses Plugin, entwickelt von AlphaattackGermany, schützt Ihren Server vor Abstürzen und sorgt für einen stabilen Betrieb.

## Installation

### Voraussetzungen

*   [Java Development Kit (JDK) 8 oder höher](https://www.oracle.com/java/technologies/javase-downloads.html)
*   [Apache Maven](https://maven.apache.org/download.cgi)

### Schritt-für-Schritt-Anleitung

1.  **Download des ZIP-Archivs:**

    Laden Sie die neueste Version von CrashGuard.zip aus dem [Repository](https://github.com/AlphaattackGermany/Anti-CrashPlugin/blob/a8e46288d05a74e23a18028213707b94997a1f92/CrashGuard.zip) herunter.
2.  **Entpacken des ZIP-Archivs:**

    Entpacken Sie die heruntergeladene `CrashGuard.zip` in einen lokalen Ordner Ihrer Wahl. Zum Beispiel: `C:/crashguard`.
3.  **Öffnen der Eingabeaufforderung oder PowerShell:**

    Öffnen Sie die Eingabeaufforderung (cmd) unter Windows oder Microsoft PowerShell.
4.  **Navigieren zum Projektverzeichnis:**

    Verwenden Sie den Befehl `cd`, um in das Verzeichnis zu wechseln, in das Sie die ZIP-Datei entpackt haben.

    ```bash
    cd C:/crashguard
    ```
5.  **Ausführen des Maven-Builds:**

    Führen Sie den folgenden Maven-Befehl aus, um das Projekt zu kompilieren und ein Package zu erstellen:

    ```bash
    mvn clean package
    ```

    Dieser Befehl führt die folgenden Schritte aus:

    *   `clean`: Bereinigt das Projekt, indem alle vorherigen Build-Artefakte entfernt werden.
    *   `package`: Kompiliert den Quellcode und erstellt eine JAR-Datei.
6.  **Finden der JAR-Datei:**

    Nachdem der Build abgeschlossen ist, finden Sie die generierte JAR-Datei im `target`-Ordner des Projekts. **Wichtig:** Verwenden Sie die JAR-Datei, die *nicht* den Zusatz "original" im Namen trägt (z.B. `crashguard-plugin-2.1.4.jar`).
7.  **Installation des Plugins:**

    Kopieren Sie die JAR-Datei in den `plugins`-Ordner Ihres Servers.
8.  **Neustart des Servers:**

    Starten Sie Ihren Server neu, damit das Plugin geladen wird.

## Konfiguration

Beschreibe hier, wie das Plugin konfiguriert wird. Zum Beispiel:

Die Konfigurationsdatei befindet sich unter `plugins/CrashGuard/config.yml`. Hier können Sie verschiedene Einstellungen anpassen, wie zum Beispiel:

*   `Parameter1`: Beschreibung von Parameter1
*   `Parameter2`: Beschreibung von Parameter2

## Befehle

Hier ist eine Liste der verfügbaren Befehle:

*   `/crashguard reload` - Lädt die Konfiguration neu.

    ```bash
    /crashguard reload
    ```

## Berechtigungen

Hier ist eine Liste der Berechtigungen:

*   `crashguard.reload` - Erlaubt das Neuladen der Konfiguration.

## Unterstützung

Bei Fragen oder Problemen besuchen Sie bitte den [GitHub Issues](https://github.com/AlphaattackGermany/Anti-CrashPlugin/issues)-Bereich des Projekts.

## Lizenz

Dieses Projekt ist unter der [MIT Lizenz](https://opensource.org/licenses/MIT) lizenziert.

## Mitwirkende

*   AlphaattackGermany

## Danksagung

*   An alle Mitwirkenden und Unterstützer dieses Projekts.
