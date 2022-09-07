# Multi-Channel-Signal-Viewer
A Digital signal processing desktop app using python and PyQt5 where users browse for multiple signals, plot signals and spectrograms, control speed, frequency, display, and color.

## Introduction
Monitoring the vital signals is a crucial aim in any ICU room.

## Description
A multi-channel signal viewer that has the following features:
- The user can browse his PC to open any signal file (e.g. ECG, EMG, EEG,…etc). 
- The application contains one main graph. When the user opens a signal file, it shows up on your 
graph in the cine mode (i.e. a running signal through time, similar to the one you see in the ICU monitors).
- The user can manipulate the running signals through UI elements that provide the below function:
• Change color
• Add a label/title for each signal
• Show/hide
• Control/customize the cine speed
• Zoom in/out
• Pause/play
• Scroll/Pan the signal is any direction (left, top, right, bottom). Scroll is through sliders, and pan is 
through the mouse movements.
- For each opened signal, the user can visualize the signal spectrogram.
- The user can control/customize the relative size of the signal graph and the spectrogram image via
dragging a splitter.
- The UI can display several signals but only one spectrogram (for one of the displayed signals). The user 
can control which spectrogram to display via a combobox or menuitem that shows the labels/titles of 
the signals. When the user selects the label/title of the signal s/he wants, the spectrogram is 
updated accordingly.
- The color palette that is used in the spectrogram through a combo-box/drop-menu that has 5 different 
palettes to use from.
- The user can control the level of details shown in spectrogram by changing the range (i.e. min and max
values) of the pixels intensity that are displayed. The user can control this through two sliders: one for 
the min value and one for the max. Each slider goes from min and max values of the pixel 
intensities of the spectrogram.
- Exporting & Reporting: For the sake of reporting, the user can export the current status of the graph, 
spectrogram along with some data statistics on the displayed signals to a pdf file. A pdf is generated via a simple click.
- Data statistics can be mean, std, duration, min and max values for each signal. These numbers 
show up in a nice table in the pdf file. 

## Tools
- Python
- PyQt5
- QtDesigner
## Demo
- The user can browse his PC to open any signal file (e.g. ECG, EMG, EEG,…etc). 
- The application contains one main graph. When the user opens a signal file, it shows up on your 
graph in the cine mode (i.e. a running signal through time, similar to the one you see in the ICU monitors).
![]([https://github.com/Your_Repository_Name/Your_GIF_Name.gif](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/open_file.gif))

-User can use multiple channels simultaneously
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/multiple_channels.gif)

- The user can control/customize the relative size of the signal graph and the spectrogram image via
dragging a splitter.
- User can change color from a palette
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/color_splitter.gif)


- The user can manipulate running signal • Zoom in/out • Pause/play
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/play_zoom.gif)


• Show/hide
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/show_hide.gif)

• Control/customize the cine speed
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/speed.gif)

- The UI can display several signals but only one spectrogram (for one of the displayed signals). The user 
can control which spectrogram to display via a combobox or menuitem that shows the labels/titles of 
the signals. When the user selects the label/title of the signal s/he wants, the spectrogram is 
updated accordingly.
- The color palette that is used in the spectrogram through a combo-box/drop-menu that has 5 different 
palettes to use from.
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/spectro.gif)

- The user can control the level of details shown in spectrogram by changing the range (i.e. min and max
values) of the pixels intensity that are displayed. The user can control this through two sliders: one for 
the min value and one for the max. Each slider goes from min and max values of the pixel 
intensities of the spectrogram.
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/spectro2.gif)

- Exporting & Reporting: For the sake of reporting, the user can export the current status of the graph, 
spectrogram along with some data statistics on the displayed signals to a pdf file. A pdf is generated via a simple click.
- Data statistics can be mean, std, duration, min and max values for each signal. These numbers 
show up in a nice table in the pdf file.
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/pdf.gif)
![](https://github.com/yaragafar/Multi-Channel-Signal-Viewer/blob/main/gifs/pdf.png)
