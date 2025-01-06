# Xilinx ISE Installtion
Vivado Installation process

(target_to_image)=

```{figure} images/xilinx_logo.png
:align: center
:width: 240px
```

XILINX ISE INSTALLATION FOR WINDOWS 10/11

1.	Go to the website : https://www.xilinx.com/downloadNav/vivado-design-tools/archive-ise.html

Download the 14.7 

 
2.	Sign in to your account. If you have not done before, then register and then download

 
3.	Download begins.  Meanwhile we will install Virtualbox. Navigate to the website: https://www.virtualbox.org/wiki/Downloads
Select Windows Host
 

 

Double click and Install  ( Proceed , accept all terms, keep doing Yes and install it !)
You will get the below. 
 
Click FINISH. You will be able to see the below window.

KEEP THIS WINDOW OPEN AND JUST MINIMIZE IT

 

KEEP THIS WINDOW OPEN AND JUST MINIMIZE IT

4.	Once Xilinx download is finished, Unzip and double click --run the xsetup.exe file

 

5.	If it is asking to enable Java etc.. just Allow.
6.	 Make sure the Virtualization is enable
 

7.	You can follow the steps mentioned below. 
(a)	Open search bar and type : Change advanced startup options. Click that

 
(b)	Click on Advanced Startup  Restart Now
 
(c)	Your Laptop will restart. Bios will open 
(d)	Click on Troubleshoot
 

(e)	Click on UEFI Firmware settings

 
(f)	Click on Restart
(g)	Under Configuration Tab : Make sure Virtualization is enabled.

After enabling , Again run the ISE xsetup.exe file 

8.	Still if you get the Virtualization error even after enabling it , do the below
 
9.	Run the xsetup.exe file
 
Click on Next

10.	Click on Continue
 

11.	Click on I Agree, Next
 

12.	Click Next

 
13.	 I am installing in my D-drive. (You can install in C drive if you wish.)
It is important to create a directory as that will be shared with the virtual machine. So I went to D drive and created a directory first, named it as XILINX_ISE_PROJECTS . After creation of that directory, I cam back to this window and entered the path. 
Click on Next
Don’t make any mistake in this step

 
14.	 Now, 
 
Click Yes
15.	Then click Install
 
16.	Installation completed. Click OK
 
17.	On the Desktop, you shpuld be able to see the shortcuts created. 
Double click on the Project Navigator. 
 
You will see that Virtual machine has opened. Close the right side popups
 

18.	 Maximize the window 
 
19.	When you click on the ise’s Home folder, you will find that the SHARED folder “ XILINX_ISE_PROJECTS “ is also seen. All your projects must be created here inside this folder 
 
20.	Double click on the Project navigator in the virtual machine
 
21.	Now to to File New Project.    Location Browse to the folder XILINX_ISE_PROJECTS
Go to Next
 
22.	Enter Board details as shown and clock on Next and then Finish. 
 
23.	 And start with your project !!






NUMATO MIMAS V2 – SPARTAN 6 FPGA BOARD

https://numato.com/product/mimas-spartan-6-fpga-development-board/
At the bottom section, you will see DOWNLOADS. Check the below

1)	USER MANUAL: Read this for better understanding of the board
2)	DOWNLAOD CONFIGURATION TOOL WINDOWS:  Download this & keep
3)	Download Numato Lab CDC driver.  Extract the .zip file & keep
4)	Click on User constraints file. New window will pop up. Copy the entire thing in a .txt file and keep.


