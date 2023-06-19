# Loading the Loader and Switching to Long Mode
Here we will be discussing about how to load a loader file and kernal file along with discussion on protection mode and long mode
The files related to the concept is provide in this branch where each boot and loader files represents as follows
boot1.asm -> to boot with message welcome to amrita os
boot2.asm -> to check Disk extension support
boot3.asm -> to load a loader file
loader1.asm -> loader which is to be loaded and has message in it
boot4.asm -> Check for long mode is supported in your system or not
loader2.asm -> loader file for the above one
boot5.asm -> to load kernel file
loader3.asm -> loader file used for above case which displays message kernel is loaded on successful loading
boot6.asm -> to get memory information
loader4.asm -> loader file used for above case and display Get memory info done
boot7.asm -> to check if system has a20 line default with it or not
loader5.asm -> loader file used for the above one and it prints a20 line is on if it works well
boot8.asm -> to use video mode on
loader6.asm -> loader file for the above case
boot9.asm -> for protected mode
loader7.asm -> loader for the above file
boot10.asm -> for long mode
loader8.asm -> Loader for the above file
