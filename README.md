# ExamPractice-26June2025-Palak.md

**Description about the topic, what we have to do for making a bootable USB.**

# Making a bootable USB by using rufus:-

 1. For making a USB drive bootable, we generally need at least 8 GB of storage of USB.
 2. Then we need a software tool like, Rufus or the Windows Media Creation Tool.
3. The process of making a bootable USB involves, downloading the software tool from its website, download an ISO file (eg. for Windows, Ubuntu or Linux)
4. Then we have to plug our USB drive into our computer.
5. If we want to make a bootable using by using rufus, then we have to Launch the downloaded Rufus executable. 
6. In Rufus, we have to choose our USB drive from the "Device" menu, and then select the ISO file, we we want to use.
7. Then, click the start button to begin the process of making a bootable USB.
8. After, the procees get finished we have to Eject our USB from our computer, and after that we can use that USB for installing the OS.


# Making a bootable USB by using Diskpart (Command Line):-

1. To create a bootable USB drive using Diskpart, we will need to use the command prompt with administrator privileges. 
2. First, we have to identify our USB drive using list disk. Type list disk to see all available disks. Note the disk number of your USB drive and select it.
3. Then type clean Command to remove all partitions and data from the USB drive.
4. Then we can make partitions in USB drive, and make them active and format (fs=ntfs quick)
5. Then we have to assign a letter for the partition (eg. X)
6. After doing all that steps, we have to copy the files from the ISO in the USB drive, by using the command (eg. xcopy or robocopy)
7. After that our USB drive will make.
   

**[Can you do multiple boots from on key?]**
Yes, it is possible to boot from multiple operating systems on a single computer. This is commonly referred to as multi-booting or dual-booting (when referring to two operating systems).
