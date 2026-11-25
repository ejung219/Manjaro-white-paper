# Loading / startup is the most frequently reported problem state across two Manjaro forum samples, associated with AppImage, Firefox, VLC media player, Freecad appimage, Musescore, Openshot 3.0, VSCodium AppImage, and Libgio

Two samples were collected from the Manjaro Third-Party Software forum on September 21, 2026, one from the front page of the forum and one specifically regarding software related to the AppImage tag. Within these samples, how frequently are specific problem states reported among users and what is the most reported problem? Named entities from each original topic are listed alongside their reported problem states to identify recurring issues. Section one identifies the entities and problem states in the first sample and groups the entities according to their associated problem. Section two identifies the entities and problem states in the second sample. Section three groups the named entities from the second sample according to their associated problem states.

*Reply counts register discussion activity and may serve as provisional indicators of user interest or support demand. They do not independently establish the frequency, severity, or technical significance of reported problems. The priorities identified in this analysis are therefore candidates for further investigation, not recommendations for resource allocation. Engineering expertise and operational evidence are required to assess their significance and determine appropriate responses.*

---

## SECTION 1: Loading / startup problems are associated with Appimage, Firefox, VLC media player, and Freecad appimage, Installation / updating / removal problems are associated with Python 3.11, AUR repositories, Kwin, Davinci Resolve, Manjaro, and XLibre

The category table lists third-party application forum topics and named entities associated with reported problem states. What problems are most frequently reported in the sampled third-party application forum topics? The logic tree groups entities together based on problem states, allowing for patterns in reported problems to be compared.  

| topic | replies | views | tags | Named Entity 1 | Named Entity 2 | Problem |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Appimage load error (Shotcut) | 38 | 638 |  | Appimage |  | Loading / startup |
| Is it possible to install and run Python 3.11 script in virtual environment? | 17 | 3137 | plasma | Python 3.11 |  | Installation / updating / removal |
| Firefox addon:Open in VLC media player? | 16 | 621 |  | Firefox | VLC media player | Loading / startup |
| Are there instructions for how to build from source when a package is not in the repository? | 15 | 834 |  | AUR repositories |  | Installation / updating / removal |
| Firefox addon question | 14 | 313 |  | Firefox |  | Incorrect output / behaviour |
| Freecad appimage fails to start after update | 13 | 227 |  | Freecad appimage |  | Loading / startup |
| How do I install "debug package" of kwin? | 12 | 224 | plasma | Kwin |  | Installation / updating / removal |
| Zombied programs refuse to close with SIGKILL/SIGCHLD | 11 | 195 |  | SIGKILL | SIGCHLD | Power / session transitions |
| How do I install Davinci Resolve on Manjaro Linux? | 11 | 1038 |  | Davinci Resolve | Manjaro | Installation / updating / removal |
| Installing and using XLibre on Manjaro | 9 | 408 |  | XLibre | Manjaro | Installation / updating / removal |

>**TAB1 Third-Party Software category sample results ranked by number of replies, with named entities and problem states derived from subject lines.** 

```
.
└── Problem conditions/`  
    ├── Loading / startup/`  
    │   ├── Appimage`  
    │   ├── Firefox`  
    │   ├── VLC media player`  
    │   └── Freecad appimage`  
    ├── Installation / updating / removal/`  
    │   ├── Python 3.11`  
    │   ├── AUR repositories`  
    │   ├── Kwin`  
    │   ├── Davinci Resolve`  
    │   ├── Manjaro`  
    │   └── XLibre`  
    ├── Power / session transitions/`  
    │   ├── SIGKILL`  
    │   └── SIGCHLD`  
    └── Incorrect output / behaviour: Firefox`   
```

>**DIA1 Relationships between named entities and problem states, derived from the third-party software category sample, organized according to the smaller of the two sets.**

---

## SECTION 2: Third-party software entities, AppImage, Musescore, Openshot 3.0, VSCodium AppImage, and Libgio are associated with loading / startup problems.

The table names third-party software entities related to AppImage forum topics and their reported problem states. What is the most frequent problem users of these software entities report when using them? The entity table lists the reported problems from each of the forum topics alongside the named entities named in each topic.

| topic | replies | views | activity | tags | Named Entity 1 | Named Entity 2 | Problem |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Appimage \- error while loading shared libraries: libwebkit2gtk-4.0.so.37 | 16 | 9092 | appimage | apache; server; mariadb; mysql | Appimage |  | Loading / startup |
| Many AppImages have stopped working after today's update :/ | 15 | 5590 | appimage | apache; mariadb; php | Applmages |  | Freezing / unresponsiveness |
| How do I start appimages from the terminal (shortcut in /usr/bin)? | 9 | 4123 | xfce; appimage | apache; mariadb; logs | Appimages |  | Loading / startup |
| Continuous coredumps from appimagelauncherd | 9 | 2608 | plasma; appimage | mariadb; mysql | appimagelauncherd |  | Power / session transitions |
| AppImage not working \- App opens for around 2-3 seconds the closes | 4 | 4275 | appimage | plasma; raspberry-pi-4; mariadb; mysql | Applmage |  | Crashing |
| \[HowTo\] get the latest LibreOffice when released? | 4 | 8352 | flatpak; appimage | mariadb; mysql | LibreOffice |  | Installation / updating / removal |
| Lunar Client window fully transparent | 2 | 1291 | appimage | systemd; mariadb | Lunar client |  | Power / session transitions |
| Many errors with musescore | 1 | 384 | appimage | pacman; package-management; mariadb | musescore |  | Loading / startup |
| Openshot 3.0 fails to start | 1 | 911 | appimage |  | Openshot 3.0 |  | Loading / startup |
| VSCodium AppImage won't launch; symbol lookup error; libgio | 1 | 2610 | qt; appimage |  | VSCodium Applmage | Libgio | Loading / startup |

>**TAB2 Third-Party Software entity sample results ranked by number of replies, with named entities and problem states derived from subject lines.**   
	 
--- 
	  
## SECTION 3: Loading / startup problems are associated with five named entities, AppImage, MuseScore, Openshot 3.0, VSCodium AppImage, and Libgio.

The logic tree identifies which problem states affect the most third-party entities by grouping them under named problem states. What is the most prominent, recurring issue identified in TAB2? How many entities are associated with that issue? The logic tree groups together named entities from TAB2 under the primary nodes that are named after each of the reported problems in TAB2.

```
.
└── Third-Party Software Entity Search Results/  
    ├── Loading / startup/`  
    │   ├── Appimage`  
    │   ├── musescore`  
    │   ├── Openshot 3.0`  
    │   ├── VSCodium Applmage`  
    │   └── Libgio`  
    ├── Freezing / unresponsiveness: Appimage`  
    ├── Power / session transitions/`  
    │   ├── appimagelauncherd`  
    │   └── Lunar client`  
    ├── Crashing: Applmage`  
    └── Installation / updating / removal: LibreOffice`  
```

>**DIA2 Relationships between named entities and problem states, derived from the third-party software entity sample, organized according to the smaller of the two sets.**
