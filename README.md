# Welkom bij de github repository voor de Geonovum workshop: DGGS en de mogelijkheden van cloud distributed computing!


## Om te beginnen
Voor deze workshop adviseren we dat je een aantal applicaties/talen hebt geinstalleerd, namelijk:

1) Een code IDE (vscode bijvoorbeeld)
2) git, anders kan je deze repo niet gebruiken
3) python
4) Een 3D viewer voor pointclouds, zoals [cloudcompare](https://www.cloudcompare.org/)

Daarnaast heb je -vooral met python- meer kans dat de isntallatie in 1x goed gaat binnen Ubuntu.
Voor windows heb je toegang tot de windows subsystem voor linux. [Hier](https://learn.microsoft.com/en-us/windows/wsl/install) kan je zien hoe je dit moet installeren, en [hier](https://code.visualstudio.com/docs/remote/wsl) hoe je je vscode hieraan koppelt

## Voorbereiding
Zorg dat je voor aanvang van de workshop de git repo hebt gecloned en de virtuele omgeving hebt geinstalleerd. Dit doe je met de volgende commando's:

```
# Clone de repo
git clone https://github.com/SjoerdBraaksma/geonovum_workshop.git

# Ga in de repo
cd Geonovum

# installeer de venv
sh install.sh

#Indien de venv niet geactiveerd is, activeer deze met:
conda activate geonovum_pointcloud
```