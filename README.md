# Anti-CrashPlugin - CrashGuard

## Installation

1. Laden Sie die ZIP-Datei herunter:
   ```shell
   https://github.com/AlphaattackGermany/Anti-CrashPlugin/files/CrashGuard.zip
   ```

2. Entpacken Sie die ZIP-Datei im Explorer.

3. Öffnen Sie die Eingabeaufforderung oder Microsoft PowerShell.

4. Navigieren Sie in den Ordner:
   ```shell
   cd C:/crashguard
   ```

5. Bauen Sie das Plugin mit Maven:
   ```shell
   mvn clean package
   ```

6. Gehen Sie zum `target`-Ordner im Explorer und laden Sie die `.jar` herunter  
   **(NICHT DIE ORIGINAL.jar!)**

## Wichtige Hinweise

- Verwenden Sie nur die generierte JAR-Datei, nicht die mit "ORIGINAL" im Namen
- Kopieren Sie die JAR-Datei in den `plugins`-Ordner Ihres Servers
- Starten Sie den Server neu, um das Plugin zu aktivieren
