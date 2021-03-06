---
caption: xPort
title: xPort | Stand-Alone Batch Exporter Utility
description: Stand-alone utility to publish SOLIDWORKS files to html, pdf, images etc. via eDrawings applications
order: 1
---
{% youtube id: KPBQ8RnvNpQ %}

xPort module is a stand-alone (.exe) application which is utilizing SOLIDWORKS eDrawings to publish the files to a list of formats.

It is required to have eDrawings Viewer installed to use the tool, but it is not required to have SOLIDWORKS application installed. Download eDrawings by following the [link](https://www.edrawingsviewer.com/download-edrawings)

> Currently xPort only works with eDrawings 2020

The following output formats are supported:

* eDrawings Files (*.eprt, *.easm, *.edrw)
* eDrawings Zip Files (*.zip)
* eDrawings Executable Files (*.exe)
* eDrawings Web Html Files (*.html)
* eDrawings ActiveX Html Files (*.htm)
* Stereolithography Files (*.stl)
* Bitmap Files (*.bmp)
* TIFF Image Files (*.tif)
* JPEG Image Files (*.jpg)
* PNG Image Files (*.png)
* GIF Image Files (*.gif)
* PDF Files (*.pdf) - drawing files only on Windows 10

## Notes

* xPort will automatically hide all the popup messages if any are shown thus allowing the automated exports without the need of user interventions.
* xPort will process all sub-folders if folder(s) is specified as an input
* Output files will be named after input files. If file already exists, index will be added to the file name, e.g. *File (1).html*, *File (2).html*

After installation of CAD+ Toolset, xPort application can be found in the Windows Start Menu.

![xPort application in the Windows start menu](xport-start-menu.png)

xPort provides [user interface](user-interface) and [command line interface](command-line) for configuring the publishing job.