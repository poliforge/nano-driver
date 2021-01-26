# Arduino Nano FT232R Driver Installation Guide

## Step 1

* Download and extract this repo to your desired location on your computer. Then in extracted folder you will find 'CDM-2.08.28-WHQL-Certified1.zip' file extract that to your desired location.

* Plugin Nano to your computer via USB Cable Provided.

&nbsp;

<img src="https://i.imgur.com/Cw6RnZB.png" alt="Step-1 Image" width="600px"/>

&nbsp;

* Wait for Device to get Ready

&nbsp;

<img src="https://i.imgur.com/UyKiPm0.png" alt="Step-2 Image" width="600px"/>


## Step 2

* Open Device Manager. Press 'Windows Start' button on you keyboard and search for 'Device Manager' and open.

<img src="https://i.imgur.com/Xov3eGd.jpeg" alt="Step-3 Image" width="600px"/>

## Step 3

* In Device Manager, go to 'Other Devices' section and expand it, find 'FT232R USB UART'

<img src="https://i.imgur.com/N5QsGg8.jpeg" alt="Step-4 Image" width="600px"/>

* Right Click on 'FT232R USB UART' to open context menu

<img src="https://i.imgur.com/DkhZAqi.jpeg" alt="Step-5 Image" width="600px"/>

* Then click on 'Update Drivers'

## Step 4

* Click on 'Browse my computer for drivers'

<img src="https://i.imgur.com/O0RgihT.jpeg" alt="Step-6 Image" width="600px"/>

* click browse and locate the extracted folder 'CDM-2.08.28-WHQL-Certified1', select 'CDM-2.08.28-WHQL-Certified1' folder and click ok.

<img src="https://i.imgur.com/MZkrilE.png" alt="Step-7 Image" width="600px"/>

* check 'Include subfolders' Checkbox
* Click 'Next'
* Now wait while the driver gets installed

<img src="https://i.imgur.com/U834qcM.png" alt="Step-7 Image" width="600px"/>

* After installation is done, click 'Close'

<img src="https://i.imgur.com/h8kEJBx.jpeg" alt="Step-8 Image" width="600px"/>

## Step 5

* Now unplug Arduino Nano and plug again and wait for the computer to detect.
* Now open Arduino IDE
* Select Arduino Nano
* In Menubar, go to Tools > Board > Arduino Nano
* In Menubar, go to Tools > Processor > ATmega328P (Old Bootloader)

<img src="https://i.imgur.com/5yJhtHw.jpeg" alt="Step-9 Image" width="600px"/>

* In Menubar, go to Tools > Port > COM7 (or it can be any other number, do not select COM1)

<img src="https://i.imgur.com/FHGE92W.jpeg" alt="Step-10 Image" width="600px"/>

## Now you are ready to use Arduino Nano

# Happy Programming!
