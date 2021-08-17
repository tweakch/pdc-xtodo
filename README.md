# pdc-xtodo

Testprojekt für [@JiroKaya](https://github.com/JiroKaya)

## Szenario

@pdc-marketing-it hat @JiroKaya und @tweakch den Auftrag gegeben einen kleine Todo-App zu erstellen

@tweakch hat bereits das README erstellt und einige [Todos](https://github.com/tweakch/projects/pdc-xtodo) definiert. @JiroKaya soll diese nun zusammen mit @tweakch beheben.

Anschliessend können wir das Projekt an @pdc-marketing-it übergeben. 

## Benötigte Software

- powershell5 (sollte installiert sein... check > `Windows+R > powershell`)
- vscode ([download](https://code.visualstudio.com/))
- .net5.0 sdk ([download](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.400-windows-x64-installer))

## Setup der Entwicklungsumgebung

### Lokale Entwicklungsumgebung einrichten

Wir klonen nun das Projekt in deinen Entwicklungs-Ordner

Bei mir hat sich folgendes setup bewährt.

```txt
~/dev/
|__ {github-account}
   |__ {project-name}
```

Also in meinem fall sieht das so aus: 

```txt
~/dev/
|__ pdc-marketing-it/
|  |__ pdc-xtodo/
|  |__ usw...
|
|__ tweakch/
   |__ github-actions-for-ci/
   |__ usw...
```

Wenn ich z.b. ein Repository von jemand anderem herunterladen möchte, mache ich einfach das: 

```ps
cd ~/dev
md JiroKaya
cd JiroKaya
git clone https://github.com/JiroKaya/pdc-xtodo
```

Das sieht dann so aus... 

```txt
~/dev/
|__ pdc-marketing-it/
|  |__ pdc-xtodo/
|  |__ usw...
|
|__ JiroKaya/
|  |__ pdc-xtodo/
|
|__ tweakch/
   |__ github-actions-for-ci/
   |__ usw...
```

Ok, das geht nicht weil Du `pdc-xtodo` noch nicht hast. Aber genau das machen wir jetzt.

### Github workflow

Wie im Szenario beschrieben habe ich bereits vorarbeit geleistet und dieses Readme erstellt 🚀🚀🚀

Nun werden wir zusammen - in bester Open Source manier - das Projekt erstellen. 

Der Github Workflow für OpenSource projekte ist `fork > clone > commit > push > pull request` 

#### Fork

Nachdem du also die SDK und VSCode installiert hast, kannst du dieses Projekt forken
![image](https://user-images.githubusercontent.com/1404998/129704894-b5fa7a59-cab5-4467-a948-8f30fcabd614.png)

Die Todos sind hier: [tweakch/pdc-xtodo](https://github.com/tweakch) 

Diese Todos werden wir nun per Pull Requests abarbeiten. 

#### Clone 

Öffne eine Powershell (`Windows+R` > `powershell`):

```ps
md -p $HOME/dev/JiroKaya
cd $HOME/dev/JiroKaya
git clone https://github.com/JiroKaya/pdc-xtodo
cd pdc-xtodo
```

Dies erstellt dein Entwicklungsordner und `cloned` dein Repo.

### vscode über commandline öffnen

Öffne vscode im aktuellen Verzeichnis

```ps
code .
```

- [ ] evtl zeigt vscode eine Warnung an das der aktuelle Ordner nicht `trusted` ist...
![image](https://user-images.githubusercontent.com/1404998/129693720-c80c4608-d052-4980-b9ff-69dbb167f951.png)
- [ ] du kannst deinem Workspace immer vertrauen also OK...
- [ ] Empfohlene Extensions (und evtl Git) installieren
![image](https://user-images.githubusercontent.com/1404998/129694590-41eaea7e-10ed-4fdf-8a3b-9f72acb9e4a6.png)

**Damit ist das Setup der Entwicklungsumgebung abgeschlossen**

## Projekt-Struktur

## 

