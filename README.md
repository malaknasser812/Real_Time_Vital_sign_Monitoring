# SBME_DSP_SignalViewer
## **Introduction** :-
A **PyQt** application used as a **Signal Viewer** program provided with a user-friendly interface to visualize ana analyze signals and to be able to navigate through various signals, find significant information about each one and even tweak them to your desired outcome.
## Features :-
- Play and display signals in real-time.
- Playback controls for play, pause, and zoom functionality.
- Customize signal name and color for better visualization.
- Move signals between two viewers and hide one or more of them.
- Generate reports containing statistical measures for analyzed signals.
- Link viewers for synchronized playback and analysis.
- Take snapshots of your signal views for documentation or sharing.
- Speed up and down the signals as desired.
## Installation
1. Clone the repository
```sh
   git clone https://github.com/malaknasser812/SBME_DSP_SignalViewer.git
 ```
2. Install project dependencies
```sh
   pip install typing
   pip install os
   pip install PyQt5
   pip install reportlab
   pip install pandas
   pip install numpy
   pip install pyqtgraph
 ```
3. Run the application
```sh
   python main.py
```
## Libraries
- PyQt5
- pyqtgraph
- reportlab
- platypus
- numpy
- pandas
## Usage
- Playing Signals :-
  
  Open the file tab at the left hand corner it displays drop-down menu for viewer one and viewer two, choose what you want and then you can browse to choose a signal.
  
- Changing Signal Properties :-

  you can change the name of the signal on the line-edit with the word label beside it, you can also change color by pushing a button that displays various and 
  different color palettes to choose from.

 - Moving Signals To Another Viewer :-

   You can move the signal from viewer one to viewer two by clicking a button named Move To V2 and vice versa.

- Playback Controls :-

  You can pause, replay from the specified buttons or zoom in and out by clicking the buttons that have the plus and minus icons, and even speed up or down the velocity of the signal.

- Taking Snapshots :-

  You can take a screenshot of the signal, or more than one signal by clicking on the snapshot icon and save it as an image on your computer.

- Generating Reports :-

  A pdf report is generated when you click on the Generate report tab that displays a table of the statistical measures of each signal, its label and all the snapshots you captured.

- Linking Viewers :-

  Linking the two viewers together for synchronized playback and analysis of the signals, using the controls will control the two signals simultaneously.

## Our Team

- Camellia Marwan
- Hager Samir
- Farah Ossama
- Malak Nasser


  
