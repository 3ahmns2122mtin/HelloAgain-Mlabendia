# Übung01 - HelloAgain Aufgabenbeschreibung

### Projektbeschreibung: 
Wir haben ein 2D Game erstellt dessen Aufgabe es nur ist unser Background und Text zu zeigen. Weiters sollte in dieser Aufgabe geübt werden einen WebGL Build zu erstellen und diesen auf GitHub unter Pages zur Verfügung zu stellen. Die Dokumentation wird über das GitHub Readme gemacht. 

### Entwicklungsplattform: 
Mac OsBigSur, Unity 2020.3.18f1, Visual Studio Version 2019 Community

### Zielplattform: 
WebGL Referenzauflösung (960x600) https://3ahmns2122mtin.github.io/HelloAgain-Mlabendia/

### Visuelle Einblicke in das Projekt: 
<img width="1920" alt="Bildschirmfoto 2021-12-02 um 09 27 03" src="https://user-images.githubusercontent.com/90834283/144385197-ff5d0a37-4e31-45fc-9d47-14dc580518de.png">

### Anforderungen:  
- [x] Anlegen eines 2D Unityprojekts mit Namen HelloAgain-yourKürzel
- [x] In Assets einen Folder MyGame erstellen und den Scenes Folder in diesen MyGame Folder ziehen
- [x] Im Ordner Scenes die SampleScene in HelloAgain umbenennen
- [x] Im Game View Einstellung 960x600 einstellen
- [x] Der Szene ein Canvas GameObject hinzufügen
- [x] Das Canvas screenindependent einstellen: 
- [x] Canvas Componente Render Mode auf Screen Space – Camera einstellen und in Render Camera die Main Camera reinziehen.
- [x] Canvas Scaler UI Scale Mode, Scale With Screen Size einstellen und als Reference Resolution 960 x 600 einstellen.
- [x] Dem Canvas GameObject ein Text GameObject hinzufügen: „Hello again, here is yourKürzel speaking :) 
- [x] Dieses Text GameObject umbenennen in Welcome
- [x] Dem Canvas GameObject ein Image GameObject hinzufügen (Abmessung/Auflösung > 960x600)
- [x] Dieses Image GameObject umbennen in Background
- [x] Anordnung in der Hierarchy so ändern, dass der Background hinter dem Text liegt
- [x] Im Ornder Assets > MyGame  einen Ordner Sprites anlegen, alle im Projekt verwendeten Sprites, die wir hinzufügen, dort ablegen.
- [x] In das Image GameObject mit Namen Background ein Sprite in die Image Source ziehen 
- [x] Assets und ProjectSettings Folders auf GitHub laden
- [x] Readme updaten
- [x] WebGL exportieren in HelloAgain-yourKürzel > docs
- [x] Upload auf GitHub
- [x] WebGL Pages Einstellen
- [x] Link in Readme einfügen

### Optionale Aufgabenstellung:
- [ ] Grafische Aufbereitung des Projekts
- [ ] Zusätzliche Text und Sprite Elemente einfügen und platzieren
- [ ] Text visuell ändern: color, font, font style, etc.
- [ ] Textmesh pro GameObject einfügen und manipulieren 
- [x] Color Tint Playmode einstellen

### Lessons Learned:
| Neu gelernt | Wiederholung | Vertiefung | Lernstoff                                                                             |
|-------------|--------------|------------|---------------------------------------------------------------------------------------|
|             |       x       |            | Anlegen eines 2D Unityprojektes                                                       |
|     x        |              |            | Screenindependent Design für 2D Einstellung des Canvas                                |
|     x        |      x        |            | GameView Auflösung Einstellung                                                        |
|             |              |      x      | Verwendung und Manipulation von UI Elementen Text, Image                              |
|             |      x        |            | Anordnung GameObjects in Hierarchy hat Auswirkung auf Anordnung der Elemente im Spiel |
|             |      x       |            | Unity Editor Komponenten: Game View, Scene View, Hierarchy, Inspector, Project        |
|     x        |              |            | (optional) Color Tint Playmode                                                        |
|     x        |              |            | WebGL exportieren                                                                     |
|     x        |              |            | WebGL auf GitHub Pages veröffentlichen                                                |


Limitations:

Eines meiner Probleme war: WebGL stuck at 90%

Lösung: Edit -> Projectsettings -> Player -> Publishing Settings -> Compression Format auf Disabled -> Decompression Fallback Hackerl hinzufügen -> erneut builden

Copyright by Mlabendia
