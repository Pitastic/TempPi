# TempPi

TempPi liest in einem regelmäßigen Intervall von Sensoren aus und speichert sie in eine Datenbank.

Gedacht ist das System dann als Standalone Lösung für die Anzeige dieser Werte auf einer grafischen Oberfläche. Dabei wird die anzeige unter <a href='http://localhost:8080'>http://localhost:8080</a> angezeigt.

## Vorraussetzungen
- Monitor über HDMI (nur für Standalone-Betrieb)
- RaspberryPi 2 < (für GPIO-Support)<br>
Vorzugsweise mit Raspbian Jessie
- Breadboard, Verkabelung, Sensoren<br>
Nur für Anschlüsse an die GPIO Schnittstelle



## Device Support

### GPIO

- Temperatursensor
- Feuchtigkeitssensor
