JAR BAUEN
=========
Variante A (lokal): JDK 21 + Maven installieren, im Ordner "GemsPlugin" ausfuehren:
    mvn package
Die fertige Datei liegt dann in:  target/Gems-1.0.0.jar   -> in den plugins-Ordner des Servers legen.

Variante B (ohne Installation): Ordner in ein neues GitHub-Repository hochladen.
Tab "Actions" -> "Build Gems-Plugin" laeuft automatisch -> unter "Artifacts" die Gems-jar herunterladen
(enthaelt die .jar, ggf. vorher entpacken).

Variante C: Ordner in IntelliJ IDEA oeffnen -> Maven-Leiste -> Lifecycle -> package.

Server: Purpur/Paper 1.21.11 oder neuer (Speere gibt es erst ab 1.21.11), Java 21.
