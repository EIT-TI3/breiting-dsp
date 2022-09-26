# Unterlagen zu den Kursen "DSV" und "DSV auf FPGAs" 
[Course material accompanying the courses "DSP" and "DSP on FPGAs" (Digital signal processing on FPGAs)]

**ATTENTION:** If you have cloned / forked this repo, it has been renamed from `dsp_fpga` -> `dsp` and the default branch now is called `main` (2020-Sep-29).

Hier finden Sie die folgenden Materialien:
* Jupyter Notebooks zu beiden Lehrveranstaltungen und zum YouTube Channel [https://www.youtube.com/c/ChristianMunker](https://www.youtube.com/c/ChristianMunker)
* Im [aktuellen Release](https://github.com/chipmuenk/dsp/releases/latest) finden Sie als "Assets":
    - die gezippten Folien zu den YouTube Videos im Libreoffice und im PDF - Format, 
    - ein Skript mit vielen Übungsaufgaben und etwas Theorie zu den Kursen "DSV" und "DSV auf FPGAs"
    - eine Anleitung zum Umgang mit Notebooks

Nutzen Sie auch das interaktive Python Tool [pyfda](https://github.com/chipmuenk/pyfda) für Filterentwurf und -analyse und zur Simulation von zeitdiskreten Systemen!

## Jupyter Notebooks
* Kurzanleitung: https://codingthesmartway.com/getting-started-with-jupyter-notebook-for-python/ mit Video https://youtu.be/CwFq3YDU6_Y
* Jupyter Notebooks: Ein weiteres sehr gutes Video Tutorial zu Jupyter Notebooks finden Sie unter [https://www.youtube.com/watch?v=HW29067qVWk]

**[00. INTRO:](notebooks/00_Intro/_index.ipynb)** Eine kurze interaktive Einführung in Notebooks, Numpy, Scipy, Matplotlib

**[00. LAB :](notebooks/00_LAB/_index.ipynb)** Praktikumsversuche (als Jupyter Notebooks)

**[01. LTI :](notebooks/01_LTI/_index.ipynb)** Linear Time-Invariant (**LTI**) Systeme im Zeitbereich

**[02. LTF :](notebooks/02_LTF/_index.ipynb)** **LT**I Systeme im **F**requenzbereich

**[03. DFT :](notebooks/03_DFT/_index.ipynb)** Discrete Fourier Transformation (**DFT**) und FFT

**[04. WIN :](notebooks/04_WIN/_index.ipynb)** Fensterung periodischer und stationärer Signale

**[05. SPS :](notebooks/05_SPS/_index.ipynb)** **SP**ektral**S**chätzung

**[06. FIL :](notebooks/06_FIL/_index.ipynb)** Digitale **FIL**ter und Filterentwurf

**[07. FIX :](notebooks/07_FIX/_index.ipynb)** **FIX**point Systeme im Zeitbereich: Quantisierung und Wortlängeneffekte

**[08. NOI :](notebooks/08_NOI/_index.ipynb)** Fixpoint Systeme im Frequenzbereich: Quantization **NOI**se

**[09. SMP :](notebooks/09_SMP/_index.ipynb)** **S**a**MP**ling, Analog-Digital Conversion and Downsampling

**[10. INP :](notebooks/10_INP/_index.ipynb)** Upsampling, **IN**ter**P**olation und Digital-Analog conversion

**[11. SRC :](notebooks/11_SRC/_index.ipynb)** **S**ample **R**ate **C**onversion

## Jupyter Notebook Server in der Cloud
Am einfachsten können Sie mit Jupyter Notebooks interaktiv auf einem Remote Server arbeiten, Sie brauchen dann nichts auf Ihrem eigenen Rechner installieren, müssen aber natürlich online sein. Ich gebe hier keine Empfehlungen mehr, da kostenlose Services selten länger als ein paar Monate funktionieren. Die Startzeit beträgt bei den meisten Services ein paar Minuten. 

Falls Sie mit dem klassischen Jupyter Notebook Interface starten (keine Tabs), können Sie zum übersichtlicheren Jupyterlab Interface wechseln, indem Sie in der Adresszeile des Browsers `tree` durch `lab` ersetzen.

### Binder
Mit diesem Service können Sie per Knopfdruck [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chipmuenk/dsp/HEAD?urlpath=lab/tree/README.md) mit den Notebooks dieses Repos experimentieren, aber keine Änderungen dauerhaft abspeichern.

## Lokal arbeiten
Wenn Sie Python auf Ihrem Rechner installiert haben, können Sie auch offline arbeiten und haben eine bessere Performance. 

- Bei Ihnen läuft schon Python? Dann genügt ein pip install jupyterlab und Sie können aus dem Terminal jupyter lab Ihren lokalen Server starten. 
- Sie möchten kein Python installieren, aber trotzdem mit Notebooks arbeiten? Testen Sie die noch ganz frische JupyterLab Desktop Applikation (https://github.com/jupyterlab/jupyterlab-desktop)

Die Notebooks (und die Libraries) clonen Sie auf Ihren Rechner aus dem (lokalen) Terminal mit 

    git clone https://github.com/chipmuenk/dsp
    
Oder nutzen Sie die graphische Oberfläche mit `git gui` -> `Clone Repository`
  
Dazu muss ein git Client von der git homepage (http://git-scm.com/) auf Ihrem Rechner installiert sein.

Notfalls können Sie die Files auch gezippt herunterladen von  https://github.com/chipmuenk/dsp, können dann aber keine Updates holen.


## git
Es schadet nicht, ein paar git Kommandos zu beherrschen, z.B. mit Hilfe von

* [git - Der einfache Einstieg](http://rogerdudler.github.io/git-guide/index.de.html) von Roger Dudler gibt den kürzest möglichen Einstieg in die Git Bash (= Kon-
sole) - mit Cheat-Sheet! - in vielen Sprachen
* [An Illustrated Guide to Git on Windows](http://nathanj.github.io/gitguide/tour.html) (2009) gibt einen ähnlich kompakten Einstieg in die Arbeit mit dem graphischen Frontend Git GUI
* [Pro Git Book](http://git-scm.com/book/de/v2), das "offizielle" Git Buch von Scott Chacon und Ben Straub gibt es hier in ziemlich vielen Sprachen
* [Learn Git Branching](https://learngitbranching.js.org?locale=de_DE) ist eine „gamifizierte“ Variante mit Schwerpunkt Branching und Merging (auch auf Deutsch)

## Zusätzliche Resourcen
* Mark Wickert hat Juypter Notebooks und Papers zu Real-Time Audio Anwendungen erstellt: ["Real-Time Digital Signal Processing Using pyaudio_helper and the ipywidgets"](https://conference.scipy.org/proceedings/scipy2018/pdfs/mark_wickert_250.pdf) (SCIPY 2018) mit GitHub Repo [scikit-dsp-comm](https://github.com/mwickert/scikit-dsp-comm) und ["A Real-Time 3D Audio Simulator for Cognitive Hearing Science"](http://conference.scipy.org/proceedings/scipy2019/mark_wickert.html) (SCIPY 2019)
