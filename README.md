# wetterstation-dokumentation
Um die Dokumentation compilen zu können wird eine LaTeX Distribution
benötigt. Zu empfehlen ist, sich das Meta Package `texlive-most` zu installieren.

Auf einem Arch-Linux (basiertem) System:
```sh
sudo pacman -S texlive-most
```
Im Ordner dann das Dokument `wetterstation.tex` kompilieren:
```sh
pdflatex wetterstation.tex
```
**Wichtig:** Das compilen muss 2x durchgeführt werden da für
das Inhaltsverzeichis *kreuzreferenziert* werden muss.
