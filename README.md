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

### Github workflow

Wie im Szenario beschrieben habe ich bereits vorarbeit geleistet und dieses Readme erstellt... 

Nun werden wir zusammen - in bester Open Source manier - das Projekt erstellen. 

Der Github Workflow für OpenSource projekte ist `fork > clone > commit > push > pull request` 

Nachdem du also die SDK und VSCode installiert hast, kannst du das projekt hier [forken](#).  

### Lokale Entwicklungsumgebung einrichten

Wir klonen nun das Projekt klonen wir das Repository in einen Entwicklungs-Ordner

Ich arbeite seit Jahren mit folgender Struktur (hat sich bewährt).

```txt
C:/dev/
|__ {github-account}
   |__ {project-name}
```

Also in meinem fall sieht das so aus: 

```txt
C:/dev/
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
cd C:/dev
md JiroKaya
cd JiroKaya
git clone https://github.com/JiroKaya/pdc-xtodo
```

Das sieht das so aus... 

```txt
C:/dev/
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

### Projekt auf Github forken

Auf meinem github steht das Projekt bereit. 

[tweakch/pdc-xtodo](https://github.com/tweakch

(`Windows+R` > `powershell`)

### Entwicklungs-Ordner erstellen und repository clonen 

Folgenden code kopieren und in die shell einfügen
```ps
md -p C:/dev/pdc-marketing-it
cd C:/dev/pdc-marketing-it
git clone https://github.com/pdc-marketing-it/pdc-xtodo
cd pdc-xtodo
```
### vscode über commandline öffnen

```ps
code .
```

- [ ] vscode sollte eine Warnung anzeigen das der aktuelle ordner nicht `trusted` ist...
![image](https://user-images.githubusercontent.com/1404998/129693720-c80c4608-d052-4980-b9ff-69dbb167f951.png)
- [ ] Workspace immer vertrauen und OK klicken
- [ ] Empfohlene Extensions (und evtl Git) installieren
![image](https://user-images.githubusercontent.com/1404998/129694590-41eaea7e-10ed-4fdf-8a3b-9f72acb9e4a6.png)

**Damit ist das Setup der Entwicklungsumgebung abgeschlossen**

## Projekt-Struktur

## 

