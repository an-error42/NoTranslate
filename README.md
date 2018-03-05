# NoTranslate
Batch languages translation client.

![Screenshot](https://image.prntscr.com/image/el0vgBtsT1yNjQeCbvkdzg.png)

About
---

NoTranslate allows you to translate text from a language, to multiple number of languages (random or predefined), then finally to another language.

NoTranslate is written in Python and uses PyQt5.  
Standalone packaging is done by PyInstaller.

Download
---

PyInstaller standalones are available as [Releases](https://github.com/an-error42/NoTranslate/releases).

Please note that VirusTotal might give you false positives. [There's nothing we can do, unfortunately](https://github.com/pyinstaller/pyinstaller/issues?utf8=%E2%9C%93&q=virus).

- [VirusTotal for v1.0.0-standalone](https://www.virustotal.com/#/file/afd6905b4727515a43672d011c9ffc88f84c7ecf8336de4c330abf5c3d72b4ce/detection).

How-to
---

1. First, chose your source language and target language (in other words: From and To).

![First Step](https://s18.postimg.org/3u7ev9im1/image.png)

2. Then you should determine the translation mode:
  - **Random Chain Mode:** Translate text from source language to multiple random languages then to target language.
  
  ![Random Chain Mode](https://s18.postimg.org/7dtcl4irt/image.png)
  
  - **Predefined Chain Mode:** Translate text from source language to multiple user-defined languages then to target language.
  
  ![Predefined Chain Mode](https://s18.postimg.org/der1i87yx/image.png)
  
3. After the translation has finished, status bar will display some information.

![Status Bar](https://s18.postimg.org/w72wls9i1/image.png)

4. And here's how the "Info" dialog will look like.

![Info Dialog](https://s18.postimg.org/4whldvm0p/image.png)

FAQ
---

Q: How do you remove a language from the "Languages Chain" list?  
A: Simply double click on the language that you want it to be removed.

Q: Why the screenshots from "How-to" section look as if they are straight from Windows 98?  
A: I assure you it's Windows 7, but with Classic Theme enabled to improve performance.

Bugs
---

If you've found a bug, or you want to make a suggestion, please [create a new Issue](https://github.com/an-error42/NoTranslate/issues/new).

Credit
---

NoTranslate is originally made for [/r/ShingekiNoTranslation](https://www.reddit.com/r/ShingekiNoTranslation/).

Author: [/u/an-error](https://www.reddit.com/user/an-error/).

NoTranslate uses Python and PyQt5, packaged using PyInstaller.
