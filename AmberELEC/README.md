Here you will find the specific changes I have made to AmberELEC for the R36s Panel 4 and G350.

How I built this was mainly through direct manipulation and editing of the SYSTEM image, with the only things having to be compiled from source being a change to Uboot for Logo on the r36s P4 devices, a change to the kernel to allow the manipulation of the analogue sticks orientation via dtb for the G350, and a build of RetroArch 1.20. Everything else is from the August 2024 pre-release. Equally I built an ultra small version of the distribution image that contained a fake SYSTEM image, allowing me to be add my modified Squash FS to a prebuilt image.

I have also added extra libraries for python, allowing me to use pygame to create some real hacky apps for myself, and of course others to use as QOL adjustments. This also means others can create their own graphical scripts for the system if they wish, and don't have to be limited to other scripting languages.

This may not line up with their source code exactly, and there will be personal elements, like artwork and personal apps I have made, that will not be shared. For things like that you can go through the trouble of unsquashing the SYSTEM image and pull that from there.

The likes of code changes to dtb's I have created for PAN4ELEC will not be shared as these were decompiled and adapted from the stock dtb's that came with the hardwares OS. I would love to know where the original dts files came from for these dtb's, unless they are coded from scratch, which I highly doubt.
