# Arbeitszeit-Tracker-Lite

ARBEITSZEIT – ANDROID-APP (private Nutzung)
===========================================

Die Datei "arbeitszeit_app.html" ist eine vollständige, offline lauffähige
App. Sie braucht keinen Play Store, kein Internet und keine Installation von
Zusatzsoftware. Alle Daten bleiben nur auf deinem Handy.


AUFS HANDY BRINGEN & ALS APP NUTZEN
-----------------------------------
1. "arbeitszeit_app.html" auf dein Android-Handy kopieren
   (z. B. per USB in den Ordner "Download", oder per E-Mail / Cloud an dich
   selbst schicken und herunterladen).

2. Datei antippen und mit "Chrome" öffnen.
   (Falls gefragt wird, womit geöffnet werden soll -> Chrome wählen.)

3. Zum Startbildschirm hinzufügen, damit sie wie eine App startet:
   In Chrome oben rechts auf das Menü (⋮) -> "Zum Startbildschirm hinzufügen".
   Danach hast du ein Icon "Arbeitszeit" wie bei einer normalen App.

Fertig. Öffnen, Zeiten eintragen – der Rest läuft automatisch.


BEDIENUNG (3 Reiter unten)
--------------------------
KALENDER
- Oben siehst du immer dein aktuelles Arbeitszeitkonto.
- Auf einen Tag tippen -> Fenster geht auf:
    • Oben "Arbeitstag / Krankheit / Feiertag" wählen.
    • Bei Arbeitstag die echten Uhrzeiten eintragen (Handy zeigt eine
      Uhr zum Auswählen). Bis zu 3 Blöcke pro Tag, z. B.
          Block 1: 07:30 – 13:45
          Block 2: 16:00 – 20:15
      Die Lücke dazwischen ist automatisch Pause.
    • Extra-Pausen im Feld "Pause (Min.)".
    • Krankheit / Feiertag zählen automatisch als ±0 Überstunden.
  "Speichern" – die Differenz erscheint direkt im Kalender.

KONTO
- Startsaldo eintragen (deine bereits vorhandenen Überstunden), damit das
  Konto nicht bei 0 beginnt.
- Tabelle mit jeder Woche: Soll, Ist, Wochensaldo, Korrektur, Konto.
- Auf eine Woche tippen, um eine Korrektur einzutragen (z. B. -8).
- "Exportieren" / "Importieren": Sicherung als Datei anlegen bzw. laden.

EINSTELLUNGEN
- Regelarbeitszeit (Soll) je Wochentag als Uhrzeit-Blöcke.
- Rechts wird die Soll-Summe pro Tag automatisch angezeigt.
- Wochenende einfach leer lassen (= 0 h).


WICHTIG: DATENSICHERUNG
-----------------------
Die Daten liegen im Speicher des Browsers auf dem Handy. Wenn du die
Browser-Daten löschst oder das Handy wechselst, sind sie sonst weg.
Deshalb ab und zu unter "Konto -> Exportieren" eine Sicherungsdatei
anlegen. Auf einem neuen Gerät die App öffnen und dort "Importieren".


RICHTIGE .APK / PLAY-STORE-APP?
-------------------------------
Eine echte native App (.apk) lässt sich aus dieser HTML-App erzeugen –
das erfordert aber einen Build-Schritt am PC (z. B. mit Android Studio und
einem WebView-Projekt oder einem Tool wie "PWABuilder"/"Capacitor").
Sag Bescheid, wenn du das möchtest; für private Nutzung ist die Variante
oben aber der einfachste und schnellste Weg.
