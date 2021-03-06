# TempPi

TempPi liest in einem regelmäßigen Intervall von Sensoren aus und speichert sie in eine Datenbank.

Gedacht ist das System dann als Standalone Lösung für die Anzeige dieser Werte auf einer grafischen Oberfläche. Dabei wird die anzeige unter <a href='http://localhost:8080'>http://localhost:8080</a> angezeigt.

## Vorraussetzungen
- Monitor über HDMI (nur für Standalone-Betrieb)
- RaspberryPi 2 < (für GPIO-Support)<br>
Vorzugsweise mit Raspbian Jessie
- Breadboard, Verkabelung, Sensoren<br>
Nur für Anschlüsse an die GPIO Schnittstelle

### Tinkerforgelib

Um die USB-Module mit Python ansteuern zu können:

1. Python-Bindungs
  1. Auf <a href='http://www.tinkerforge.com/de/doc/Downloads.html'>http://www.tinkerforge.com/de/doc/Downloads.html</a> die Bindings für Python herunterladen.
  2. Im Verzeichnis der Bindings `sudo python setup.py install` ausführen.
  3. **alternativ:** via pip mit `pip install tinkerforge`
2. Brick Deamon
  1. siehe <a href='http://www.tinkerforge.com/de/doc/Software/Brickd_Install_Linux.html#brickd-install-linux'>offizielle Dokumentation</a>



## Device Support

### GPIO

- Temperatursensor
- Feuchtigkeitssensor

### Tinkerforge

- Temperatursensor
- Feuchtigkeitssensor
