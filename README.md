# System-Programmierung
## Hands-on Lektion 0
Hands-on zu [Lektion 0](https://github.com/tamberg/fhnw-syspr/blob/master/00/README.md)

### Hands-on, 1h: Raspberry Pi
* Raspberry Pi Setup via USB zum eigenen Computer.
* "Hello World" in C auf Raspberry Pi speichern.
* Den C Source Code mit gcc kompilieren.
* $ gcc -o hello hello.c
* $ ./hello
* Fertig? Bitte Nachbarn helfen.

## Git
Auf Ihrem Computer
* Zu Beginn jeder Lektion wird ein Hands-on Repository Link bekannt gegeben
* Nachdem Sie das "Assessment" annehmen, bekommen Sie per Email ein Repository
* Die REPO_URL enthält Ihren GitHub Account USER_NAME und Ihre Klasse 3ia oder 3ib, z.B.<br/>
            https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00-tamberg

Auf dem Raspberry Pi
* $ cd ~
* $ git clone REPO_URL
* $ git add FILE
* $ git commit FILE -m "Fixed all bugs"
* $ git push

## Nano
Auf dem Raspberry Pi
* Neue oder bestehende Datei öffnen mit $ nano FILE
* Editieren
* Speichern mit `CRTL-X` `Y` `RETURN`

## SSH
Auf Ihrem Computer
* Terminal öffnen (Mac) oder `WINDOWS` `R` cmd `RETURN` (Windows)
* $ ssh pi@raspberrypi.local

## Support
- [FHNW Syspr Slack](https://fhnw-syspr.slack.com/)
