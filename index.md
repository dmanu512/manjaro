
# AppImage suffers from loading or starting up, freezing or unresponsiveness, and incorrect behavior or output; Manjaro Linux help forum users both need help and are ready to help with AppImage

The Manjaro Linux help forum is an online forum for users of Manjaro Linux to either seek help on problems they’re facing, or to try and help those seeking help. Being a forum, this comes with threads that future users can read for reference; these threads are titled with subject lines where users posting these threads can specify what problems they face with different aspects of Manjaro Linux.

This document uses [https://gvbwilkesiv.github.io/manjaro-forum-sample-collector/](https://gvbwilkesiv.github.io/manjaro-forum-sample-collector/) to collect samples from the Manjaro Linux help forum to pin down what Manjaro Linux users struggle the most with. From this document’s findings, AppImage, an open-source format for distributing portable software in Linux, was found to be the most problematic for users, who’ve been seeking help for the problems they face with AppImage, while at the same time, experts are more than ready to help users with all of those various problems with AppImage, while also helping future users by having their solutions be searchable online.

Reply counts register discussion activity and may serve as provisional indicators of user interest or support demand. They do not independently establish the frequency, severity, or technical significance of reported problems. The priorities identified in this analysis are therefore candidates for further investigation, not recommendations for resource allocation. Engineering expertise and operational evidence are required to assess their significance and determine appropriate responses.

## Section 1: Manjaro Linux help forum users have problems with loading or starting up AppImage, and installing or updating or removing Python, Script, and build; threads made asking for help garner lots of replies, indicating lots of help is being provided

These subject lines are ranked by the number of replies the threads garnered at the time of retrieval (Sep. 23), and each row identifies third party software and problem states from said subject lines to give an idea of what Manjaro Linux users struggle with. By ranking by replies, topics with the most experts trying to help rank on top.


| sample_number | topic | replies | views | tags | Named Entity 1 | Named Entity 2 | Named Entity 3 | Problem |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 49 | Appimage load error (Shotcut) | 38 | 649 |  | AppImage |  |  | Loading / startup |
| 6 | Is it possible to install and run Python 3.11 script in virtual environment? | 17 | 3144 | plasma | Python | Script |  | Installation / updating / removal |
| 70 | Firefox addon:Open in VLC media player? | 16 | 634 |  | Firefox |  |  | Incorrect output / behaviour |
| 73 | Firefox addon question | 14 | 322 |  | Firefox |  |  | Unclear / Unspecified |
| 2 | Freecad appimage fails to start after update | 13 | 244 |  | AppImage | Update |  | Loading / startup |
| 34 | Cannot build OpenShot | 12 | 496 |  | build |  |  | Installation / updating / removal |
| 56 | How do I install "debug package" of kwin? | 12 | 230 | plasma | kwin |  |  | Installation / updating / removal |
| 81 | Burn bootable Windows 10 ISO image to USB stick with dd? | 11 | 2701 |  | Windows | ISO | USB | Recognition / detection |

>*This category table, **TAB1**, contains subject lines from the Manjaro Linux help forum, narrowed down to threads posted under the Third Party Program section, and further narrowed down to omit subject lines not containing named entities.*  


  

```
└── Third-Party Software Category Search Results/
├── Loading / Startup/
│ ├── AppImage
│ └── Update
├── Installation / updating / removal/
│ ├── Python
│ ├── Script
│ ├── build
│ └── kwin
├── Recognition / detection/
│ ├── Windows
│ ├── ISO
│ └── USB
├── Incorrect output / behavior: Firefox
└── Unclear / unspecified: Firefox
```
>*This logic tree, **DIA1**, groups the third party software under the problem states identified under each subject line in **TAB1**, cleaning up where each software goes under which category.*

## Section 2: Manjaro Linux users struggle the most with loading or starting up AppImage, while also suffering from other issues such as freezing or unresponsiveness and incorrect behavior or output; threads made asking for help specifically with AppImage garner even more replies, indicating even more help is being provided

Every subject line contains the software AppImage, which was the one identified in the subject line with the most replies in TAB1. By narrowing down the search to just AppImage, we can get a look at what other problems users face when dealing with AppImage.


| sample_number |                                   topic                                  | replies | views |        tags       | Named Entity 1 | Named Entity 2 |              Problem              |
|:-------------:|:------------------------------------------------------------------------:|:-------:|:-----:|:-----------------:|:--------------:|:--------------:|:---------------------------------:|
|             7 | Appimage - error while loading shared libraries: libwebkit2gtk-4.0.so.37 |      16 |  9102 | appimage          | AppImage       |                | Loading / startup                 |
|            18 | Many AppImages have stopped working after today's update :/              |      15 |  5595 | appimage          | AppImage       | Update         | Freezing / unresponsiveness       |
|             3 | AppImages kann ich nicht mehr öffnen                                     |      14 |   344 | appimage          | AppImage       |                | Loading / startup                 |
|             5 | New DeLinuxCo Cinnamon ISO with pre-installed AppImages                  |       9 |   674 | appimage          | AppImage       | ISO            | Unclear / Unspecified             |
|            11 | How do I start appimages from the terminal (shortcut in /usr/bin)?       |       9 |  4133 | xfce; appimage    | AppImage       | Terminal       | Loading / startup                 |
|            23 | Continuous coredumps from appimagelauncherd                              |       9 |  2616 | plasma; appimage  | AppImage       | Coredump       | Incorrect output / behaviour      |
|            17 | Appimage rawtherapee lässt sich nicht mehr starten                       |       8 |  1576 | appimage          | AppImage       |                | Loading / startup                 |
|            14 | AppImage not working - App opens for around 2-3 seconds the closes       |       4 |  4281 | appimage          | AppImage       |                | Crashing                          |
|            26 | [HowTo] get the latest LibreOffice when released?                        |       4 |  8358 | flatpak; appimage | AppImage       | LibreOffice    | Installation / updating / removal |
|             4 | Pcsx2 appimage (execv error: No such file or directory)                  |       2 |   944 | appimage          | AppImage       |                | Recognition / detection           |

>*This second table, **TAB2**, is the entity search table, also derived from the Manjaro Linux help forum. *

## Section 3: AppImage suffers from loading or starting up, freezing or unresponsiveness, crashing, and incorrect output or behavior

  
AppImage is associated with at least 7 different problems; this many problems associated with AppImage means that this program is very prone to breaking. Experts on the Manjaro Linux help forum must be prepared to help with all of these problems associated with AppImage.
```
    └── Third-Party Software Entity Search Results/
    ├── AppImage/
    │ ├── Loading / startup
    │ ├── Freezing / unresponsiveness
    │ ├── Crashing
    │ ├── Incorrect output / behaviour
    │ ├── Installation / updating / removal
    │ ├── Recognition / detection
    │ └── Unclear / unspecified
    ├── Update: Freezing / unresponsiveness
    ├── ISO: Unclear / unspecified
    ├── Terminal: Loading / startup
    ├── Coredump: Incorrect output / behaviour
    └── LibreOffice: Installation / updating / removal
```
>*This logic tree, **DIA2**, is derived from the data in TAB2. Because there are less named entities than problem states, the problem states are grouped under the named entities. This kind of grouping allows us to see clearly what problems AppImage can face.*

