
  NX                                                               VERSION  2206.9220

  Windows (64 Bit)                                             Issued:     April 2024



  Files on this media are intended for use on supported 64 bit Windows
  platforms only.

  The software will not work on 32 bit machines.
 
  ____________________________________________________________________________
  DOWNLOADING/EXTRACTING NX:

  There are two options to download NX. The first option is recommended for customers
  who are running the most recent versions of NX (2206 Series).  

  Download the zip file containing the MSP update files.  This zip file is titled:

  SiemensNX-2206.9220_wntx64_MSP.zip

  The second option is recommended for customers who are not on the most recent
  version of NX. This zip file is titled:
  
  SiemensNX-2206.9220_wntx64.zip
  
  After downloading the zip file, you can use certutil to verify that the SHA-512 hashvalue 
  matches between the zip file and the hash listed in the full or MSP SHA512 zip file.

  For MSP, use the command:

     certutil -hashfile SiemensNX-2206.9220_wntx64_MSP.zip SHA512

  For Full, use the command:

     certutil -hashfile SiemensNX-2206.9220_wntx64.zip SHA512
  
  ____________________________________________________________________________
  RETURN TO PREVIOUS VERSION SUGGESTION:

  Note: Once the upgrade from the previous NX release completes, if you uninstall
  NX using Add/Remove programs it will remove all of the NX 
  installation, not just the files updated with this NX version. 
  This includes Start Menu items and registry settings.

  To return to a previous version of NX, it is recommended that you 
  uninstall this version and then reinstall using the original media for
  the previous NX version.
 
  ____________________________________________________________________________
  UPDATE INSTRUCTIONS:

  The installation is being provided in two formats:
  
  1)  MSP format.  This is an upgrade only patch installer that will upgrade your previous
         NX version to the current version.  This is available as download only.
		 
  2)  MSI format.  This is a complete installation provided in the download ZIP file.
		 
         The MSI-based installer is designed to update (upgrade) existing NX 
		 installations or allow the base install of this NX release if 
	     NX is not previously installed on a system.
		 
  See the docs\nx_install_wnt.pdf installation guide for more information on
  the full and update installations. Below are the brief instructions on
  upgrading NX releases.
  

  UPGRADE INSTALLATION WITH MSP INSTALLER:
  
  To install NX as an upgrade to a previous NX release with 
  the MSP installer, follow these steps:
  
    1. Log onto your workstation using an account with Administrator privileges.
	
    2. Use File Explorer to locate the downloaded MSP file.

    3. Extract the zip SiemensNX-2206.9220_wntx64_MSP.zip file.

    4. Double-click on the setup.exe file in the folder created by the zip file.
	
    5. Follow the prompts to Update the installation of NX.
	
  SILENT UPGRADE WITH MSP INSTALLER:
  
  The installation of NX as an upgrade can also be accomplished by 
  an automatic, unattended install. This feature may aid those System Administrators
  with a large number of site installations.
  
  Caution:
  Use of this type of installation is intended for experienced installers only.

  Performing an unattended upgrade installation can be done with the command line:

    setup.exe /s /v"/qn+ /L*v c:\temp\upgrade.log"

  This will update installed files in the NX environment to the new NX 
  version of the files.  The setup.exe will update the product using all of the available
  MSP files in the same location as setup.exe.  Do not rename, remove or add MSP files to 
  this location as it will invalidate the update installation.

  Note:  The + on the /qn+ will pop-up an end dialog when the install is complete.
  If you want a completely silent installation with no pop-up, omit the +.
  
  
  UPGRADE INSTALLATION WITH MSI INSTALLER:

  To install NX as an upgrade to a previous NX release, follow 
  these steps:

    1. Log onto your workstation, using an account with Administrator privileges.

    2. Unzip the downloaded file.

        Double-click on the program Launch.exe in the top level folder.

    3. Select "Install Siemens NX" from the media Launch.exe program (if available). 
       OR
       Using File Explorer, navigate directly to the NX folder on the DVD 
       drive, and double-click on setup.exe to start the setup program.

    4. A dialog stating: “This setup will perform an upgrade of 
       ‘NX’ Do you want to continue?” will be shown. Click "Yes".

    5. At the Welcome dialog, click Next to continue. 

    6. Click Install to begin the upgrade of NX. Clicking on the Cancel button 
       at anytime during the installation will discontinue (and roll back) the installation.

  SILENT UPGRADE WITH MSI INSTALLER  
  
  The installation of NX as an upgrade can also be accomplished by 
  an automatic, unattended install. This feature may aid those System Administrators
  with a large number of site installations.
  
  Caution:
  Use of this type of installation is intended for experienced installers only.

  Performing an unattended upgrade installation can be done with the command line:
    start /wait msiexec.exe /i SiemensNX.msi /qn /L*v c:\temp\upgrade.log REINSTALL=ALL REINSTALLMODE=vomus

  This will update installed files in the NX environment to the 
  NX new version of the files.

  _____________________________________________________________________________
  INSTALLATIONS: 

  To install the products on this media, run the 'Launch.exe' program at
  the top level, or change directory to the product directory and 
  run the setup program contained within that directory.  

  See the installation guide in the docs directory or from the link on the
  Launch.exe program to view the installation instructions.

  _____________________________________________________________________________
  DOCUMENTATION:

  The 'docs' folder contains Installation documents and other related
  documents, which may be viewed or printed with your browser.

  NOTE:  Viewing Documentation directly from the media Launcher will
         require that the Adobe Acrobat plug-in is installed on your
         system.  No errors are given if the plug-in is not available.

         Download the plug-in from:  http://www.adobe.com/acrobat
		 
  _____________________________________________________________________________
  RELEASE INFORMATION:

  The 2206 What's New Guide and the Release Notes are available on the web.

  Once installed, both documents can be viewed from the start menu:

  Start -> Programs -> Siemens NX -> Release Information -> 

  	*What's New
  	*Release Notes

    _____________________________________________________________________________
  OSS SOURCE CODE:
  
  Where there is a license obligation to provide you with source code you can apply in writing to;
                Siemens Legal (LC TE SL) 
                Werner-von-Siemens-Str. 60, 
                91052 Erlangen 
                Germany
  Alternatively, it may be found at https://download.industrysoftware.automation.siemens.com/open-source/

  _____________________________________________________________________________