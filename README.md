# Rikus Desktopuhr

**A clock on your Xfce desktop — four clocks to choose from, behind all your windows.**
Free of charge, no sign-up, no code.

➡️ **Website and download: https://desktopuhr.rikus.info**

---

## 🇬🇧 English

### What it does

Rikus Desktopuhr puts a clock right onto your wallpaper: behind all windows, without a
button in the panel, on every workspace — like a clock on the wall.

- **Four clocks:** Ring, Glass card, Classic hands and Minimal hands. Each one lets you
  switch three things on and off, for example the seconds or the date.
- **Classic hands** shows the date in a small window, like a real watch: *Tue 22 Sep*.
- **Move it** with the mouse or pick one of nine fixed places. The clock remembers where it was.
- **Size** from 70 to 140 percent, three Rikus colours, light and dark — dark is anthracite, never black.
- **See-through background**, from solid to invisible. Each clock remembers its value,
  separately for light and dark.
- **A right-click** on the clock opens “Einstellungen” (settings) and “Schließen” (close).
- **Starts by itself** after you log in — you can switch that off in the settings.
- Weekday and date on the clock follow your computer’s language — German or English.
  The settings window speaks German.

### Install (Xfce — for example MX Linux or Linux Mint with Xfce)

Add the package repository once:

```sh
sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Then install:

```sh
sudo apt update && sudo apt install rikus-desktopuhr
```

Then click “Rikus Desktopuhr” once in the start menu — from your next login on it comes up
by itself. To remove the repository again (the clock stays installed):

```sh
sudo rm /etc/apt/sources.list.d/rikus.list /etc/apt/keyrings/rikus.gpg && sudo apt update
```

Or download the file directly on **https://desktopuhr.rikus.info**.

### What you need

**The Xfce desktop.** On other desktops such as GNOME, KDE or Cinnamon the clock has not
been tried out yet, so its start-menu entry does not appear there. For the see-through
background, compositing has to be switched on in Xfce — on MX Linux it is on out of the box.

### Current version

**0.9** (22 September 2026) — the first version.
All changes, in German and English: https://desktopuhr.rikus.info/aenderungen

### Where the code lives

This page is the **contact point**, not the source archive. The program is delivered through
the website and the package repository above, not from here.
Use **Issues** for bug reports and questions — or write through the form on the website:
https://desktopuhr.rikus.info/schreiben

---

## 🇩🇪 Deutsch

### Was es macht

Rikus Desktopuhr stellt eine Uhr direkt auf dein Hintergrundbild: hinter alle Fenster,
ohne Knopf in der Leiste, auf jede Arbeitsfläche — wie eine Uhr an der Wand.

- **Vier Uhren:** Ring, Glaskarte, Zeiger klassisch und Zeiger minimal. Bei jeder lassen
  sich drei Dinge ein- und ausschalten, zum Beispiel Sekunden oder Datum.
- **Zeiger klassisch** zeigt das Datum in einem kleinen Fenster, wie bei einer echten Uhr: *Di 22. Sep*.
- **Verschieben** mit der Maus oder eine von neun festen Lagen wählen. Die Uhr merkt sich ihren Platz.
- **Größe** von 70 bis 140 Prozent, drei Rikus-Farben, Hell und Dunkel — Dunkel ist Anthrazit, nie Schwarz.
- **Durchsichtiger Hintergrund**, von deckend bis unsichtbar. Jede Uhr merkt sich ihren
  Wert, für Hell und Dunkel getrennt.
- **Ein Rechtsklick** auf die Uhr öffnet „Einstellungen“ und „Schließen“.
- **Startet von selbst** nach dem Anmelden — das lässt sich in den Einstellungen abschalten.
- Wochentag und Datum auf der Uhr folgen der Sprache des Rechners — Deutsch oder Englisch.

### Installieren (Xfce — zum Beispiel MX Linux oder Linux Mint mit Xfce)

Die Paketquelle einmal eintragen:

```sh
sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Dann installieren:

```sh
sudo apt update && sudo apt install rikus-desktopuhr
```

Danach im Startmenü einmal auf „Rikus Desktopuhr“ klicken — ab dem nächsten Anmelden kommt
sie von selbst. Die Paketquelle wieder loswerden (die Uhr bleibt installiert):

```sh
sudo rm /etc/apt/sources.list.d/rikus.list /etc/apt/keyrings/rikus.gpg && sudo apt update
```

Oder die Datei direkt auf **https://desktopuhr.rikus.info** herunterladen.

### Was du brauchst

**Den Xfce-Desktop.** Auf anderen Oberflächen wie GNOME, KDE oder Cinnamon ist die Uhr noch
nicht erprobt; ihr Eintrag im Startmenü erscheint dort deshalb nicht. Damit der Hintergrund
durchsichtig sein kann, muss in Xfce das Compositing eingeschaltet sein — bei MX Linux ist es
das von Haus aus.

### Aktuelle Fassung

**0.9** (22. September 2026) — die erste Fassung.
Alle Änderungen, deutsch und englisch: https://desktopuhr.rikus.info/aenderungen

### Wo der Quelltext liegt

Diese Seite ist die **Anlaufstelle**, nicht das Archiv des Quelltextes. Das Programm kommt über
die Webseite und die Paketquelle oben, nicht von hier.
Fehler und Fragen bitte unter **Issues** — oder über das Formular auf der Webseite:
https://desktopuhr.rikus.info/schreiben

---

## More free programs / Weitere kostenlose Programme

All Rikus programs / Alle Rikus-Programme: **https://programme.rikus.info**

## Nutzungsbedingungen / Terms of use

Copyright (C) 2026 Gilbert Rikus. **Alle Rechte vorbehalten. All rights reserved.**

Benutzen ist kostenlos. Vervielfältigen, Verändern und Übernehmen in eigene Programme sind
**nicht** gestattet. Der vollständige Text liegt jedem Paket als `LICENSE` bei.

Use is free of charge. Copying, modifying and reusing it in your own programs are **not**
permitted. The full text ships with every package as `LICENSE`.

---

© Gilbert Rikus · https://rikus.info
