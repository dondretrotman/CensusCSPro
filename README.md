Census Android CAPI application  
Author: Dondré Trotman  
Date: 2018/05/24  
Version: 0.2  
  
Description:  
This application is meant to be installed on an Android device using the CSPRO app available on the Google Play Store.  
It is based on the 2020 Barbados Population and Housing Census questionnaire which is still under development.  
To run on desktop, it needs the following file extensions, all with the same name:  
.ent, .net.apc, .ent.mgf, .ent.qsf, .fmf, .pff  
To run on Android, it needs for following file extensions, all with the same name:  
.pff, .pen. Copy the two files to the csentry folder on an android device that has CSPro installed    
Search for DEBUG: to find code with known bugs   
Search for TODO: to find more things to add  
  
Special instructions:   
Make sure that the order of the individual Listing and the population section are the same.  
  
TODO:  
Make sure that android experience is good  
Add metadata. i.e. Enumerator ID, Supervisor ID and Interview status.  
ask about encrypting CSPro csdb files  
     
ISSUES:  
When synchronised from the web, the Menu app does not launch the Visitation Record or the Census Questionnaire. Works fine in windows.
