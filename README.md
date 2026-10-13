# Hexfire

Koop-Roguelite für bis zu vier Spieler, von oben gesehen. Ein privates Projekt unter Freunden,
alles ist noch im Bau und die Grafik sind Platzhalter.

## Herunterladen

1. Rechts auf **Releases** gehen und beim neuesten **`Hexfire.exe`** laden
   (oder `Hexfire.zip`, wenn der Browser die exe nicht mag).
2. Die Datei in einen eigenen Ordner legen und starten. Installiert wird nichts.
3. Windows warnt beim ersten Start, weil die Datei nicht signiert ist:
   **Weitere Informationen**, dann **Trotzdem ausführen**.

## Auf dem Stand bleiben

Im Hauptmenü unten steht die Fassung. **Nach Update suchen** fragt hier nach, ob es eine neuere
gibt, lädt sie und startet das Spiel neu. Beim Start sieht das Spiel auch von selbst einmal nach.

**Alle Mitspieler brauchen dieselbe Fassung.**

## Zusammen spielen

- Einer klickt auf **Spiel hosten**. Darunter steht die Adresse, die die anderen brauchen.
- Die anderen tragen diese Adresse ein und klicken auf **Beitreten**.
- Über das Internet geht das mit [Tailscale](https://tailscale.com): Der Host teilt seinen Rechner
  mit den Mitspielern, die tragen seine Tailscale-Adresse ein (beginnt mit `100.`).
- Das Spiel benutzt den Port 24565 über UDP. Fragt die Windows-Firewall beim Host, zulassen.

## Steuerung

| Taste | Was sie tut |
| --- | --- |
| W A S D | laufen |
| Maus | zielen, Linksklick greift an |
| Leertaste | ausweichen |
| Q, rechte Maustaste | die beiden Fähigkeiten der Klasse |
| 1 bis 4 | Waffe wechseln |
| R | nachladen |
| G | Heiltrank |
| F | Truhe öffnen, Händler, aufheben |
| Tab | Inventar |
| E | am Ausgang die anderen herrufen |
| ^ (links neben der 1) | Debug-Fenster: Gegner, Gegenstände und Orte herbeiholen |
| Esc | zurück ins Menü |
