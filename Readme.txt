                                                                   CoFSM Executable
Paper: "CoFSM:Multi-modal Remote Sensing Image Matching Considering Co-occurrence Filter"
Code:
 0. Introduction of executable program packages:

     The code is closed under the matlab r2018a version.
      CoFSM.exe in the“for_redistribution_files_only”folder and “CoFSM.exe”are an executable program.
    (1) If you have already installed matlab, please run CoFSM.exe according to the following instructions.
     >> Parameters.txt  %% This file sets the path of image input and output and the settings of core parameters.
      >> Parameters.txt 
	>> The 1 line is the path of the reference image;(Custom path)
	>> The 2 line is the path of the Image to be matched;(Custom path)
	>> The 3 line is the initial window of co-occurrence filtering;(The default is 5)
	>> The 4 line is the number of scale space layers; (The default is 4)
	>> The 5 line is the feature point extraction threshold;  (The default is 1300)
	>> The 6 line is the saved matching results;(Custom path)
	>> The 7 line is the Corresponding point file of the matching result.(Custom path)

	>>Running CoFSM.exe
	-- Open  CMD.exe
	  firstly, input "CoFSM.exe";
	  then,    input "Parameters.txt"
	-- Click on "Enter".
    --------------------------------------------------------------------------------------------------
    (2) If you have not installed matlab, please refer to 1 and the following introduction.
    The MyAppInstaller_mcr.exe in the "for_redistribution" folder is the MCR installation package.

1. Prerequisites for Deployment 

Verify that version 9.4 (R2018a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2018a 
from the following link on the MathWorks website:

    http://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
Package and Distribute in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-CoFSM.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
http://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.




