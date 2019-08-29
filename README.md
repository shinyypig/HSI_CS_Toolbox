# HSI_CS_Toolbox

## Description

This is a matlab toolbox for hyperspectral image compression. The code is derived from "Hyperspectral Image Compression Using JPEG2000 and Principal Component Analysis". The basic idea of this paper is to use JPEG2000 to compress the selected principal components.

## Installation

Go to the [release page]('https://github.com/shinyypig/HSI_CS_Toolbox/releases') and download the **HSI_CS_Toolbox.mlappinstall** file. Then open your MATLAB to install it, after installation, you can find it in the **APPS** tab.

## Usage

- Compression: click the *Select Files* button and select the files (the data file, not the .hdr file, multifiles is supported). The selected files would be shown in the listbox, then you can use the sliders to change the parameter. Click the *Run* button to begin compressing. At last the compressed files is generated in the same folder of the image data, named **Compressed**.

- Decompression: click the *Select Files* button and select the files(.tar). Click the *Run* button to begin decompressing. At last the compressed files is generated in the same folder of the compressed data, named **Decompressed**.

## GUI

![Compression Interface](https://github.com/shinyypig/HSI_CS_Toolbox/blob/master/pics/1.jpg)
![Decompression Interface](https://github.com/shinyypig/HSI_CS_Toolbox/blob/master/pics/2.jpg)
![Help Interface](https://github.com/shinyypig/HSI_CS_Toolbox/blob/master/pics/3.jpg)

## Attention

The app is written in MATLAB 2019a and only tested in 2018a and 2018b. This toolbox now only supports hyperspectral image files with .hdr. 

## Thanks

The JPEG2000 codec used in this toolbox comes from [OPENJPEG]('https://github.com/uclouvain/openjpeg').
