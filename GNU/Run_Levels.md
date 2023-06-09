# RunLevels
Enables the level to be activated and loaded.

![run_steps](../Images/run_steps.png)
## Power On Self Test

as first step will be  the hardware testet, that is from BIOS read . 
when all hardware is functional goes to next step (MBR)

## MBR 
Any Opersaion System will be searcht , that is defined in BIOS defined. MBR is the first 512 B long Sector in the disk. MBR gives info for the File_System and Operating_System. GRUB_info is also heer kept. 

## GRUB
In the Opening_Phase will be shown a Menü of possible OS. The Starting of OS beins based on some parameters, special for choosen OS. 

## Kernel (initrd) 
It is an image called initial RAMdisk. It is a temporary file that helps during the kernel and real file system loading. All directories are mounted here to the operating system. Its function ends when the operating system is successfully loaded.

## init
After installing the kernel properly, its initial process 'init' is started. It starts the process defined at the running level (runlevels) of the system.




![run_levels](../Images/run_levels.png)