# Windows-on-RPI-2-3
How to install Windows 10 ARM64 on raspberry pi 2/3
(Windows software is quite slow on the Raspberry Pi)

# Equipment:
1. SD card (at least 16GB or more)
2. Windows PC running Windows 10
3. Microsoft Edge (downloaded on your Windows PC

# Installing Windows
Open https://uup.rg-adguard.net in Microsoft Edge.
In the first option choose 'Windows (Final Version)'.
In the second option use the most recent update that ends with '[arm64]'.
In the third option choose your launguage.
In the fourth option choose 'Windows 10 Home'.
In the last option choose 'Download ISO compiler in OneClick! (run downloaded CMD-file)'.

Your links should show up to the right side of the page and choose your first link which will download your CMD-file.
Your computer will show '(your file) was blocked because it could harm your device', click 'more, run anyway.
In your file explorer create a folder and copy your CMD-file into it.
Open your CMD-file and click 'more', run anyway.
Your download will take 10mins-1hour, when it has finished it will prompt you to press a key to finish, press your space bar and it will exit.

# Installing Windows onto your SD card
Insert your SD card into your computer.
Open worproject.ml in Microsoft Edge and download the latest version of the WOR Imager tool.
Extract your file to it's own folder and run it.
Follow the instructions on the WOR imager tool and when it askes you to upload your windows file, upload the disk image file from the download before.
When it asks you to upload the drivers and the EUFI firmware click download the latest version from the web.
Once it has finished downloading, place your SD card into your raspberry pi and follow the setup instructions.

# You have now finished your very own Windows RPI PC!
