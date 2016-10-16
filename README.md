# TempPi

TempPi liest in einem regelmäßigen Intervall von Sensoren aus und speichert sie in eine Datenbank.

Gedacht ist das System dann als Standalone Lösung für die Anzeige dieser Werte auf einer grafischen Oberfläche. Dabei wird die anzeige unter <code>http://localhost:8080</code> angezeigt.

## Vorraussetzungen

### Monitor über HDMI (nur für Standalone-Betrieb)

### RaspberryPi 2 < (für GPIO-Support)

Vorzugsweise mit Raspbian Jessie

### Breadboard, Verkabelung, Sensoren

Nur für Anschlüsse an die GPIO Schnittstelle

### Tinkerforgelib

Um die USB-Module mit Python ansteuern zu können:

1. Python-Bindungs
1a. Auf <a href='http://www.tinkerforge.com/de/doc/Downloads.html'>http://www.tinkerforge.com/de/doc/Downloads.html</a> die Bindings für Python herunterladen.
1b. Im Verzeichnis der Bindings `sudo python setup.py install` ausführen.
1c. **alternativ:** via pip mit `pip install tinkerforge`
2. Brick Deamon
2a. siehe <a href='http://www.tinkerforge.com/de/doc/Software/Brickd_Install_Linux.html#brickd-install-linux'>offizielle Dokumentation</a>



## Device Support

### GPIO

- Temperatursensor
- Feuchtigkeitssensor

### Tinkerforge

- Temperatursensor
- Feuchtigkeitssensor
