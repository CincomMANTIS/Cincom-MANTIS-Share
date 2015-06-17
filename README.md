# Cincom-MANTIS-Share
MANTIS is a high level programming platform optimized to crank out "line of business" applications across all major commercial platforms.
It allows focus on business data and process instead of technology. However, access to low level technologies is available if desired or required.

How to install a MANTIS Android tablet app
------------------------------------------

* Navigate to the Applications/ANDROID folder.

* Download the .apk file of choice, preferably direct to the Android tablet.
  - Using the File Manager app on the Android device, navigate to the .apk file. 
  - Select the .apk file and it will install. 
  
* If direct download to Tablet is unavailable, use the Dropbox app!
  - NOTE: you must download and install the Dropbox app on your Android Tablet device.
  - Request access to a 'shared folder' of Dropbox maintained by Cincom.  Simply
    send an email to MantisStudio@cincom.com and we'll set you up.  Then using the 
    'shared folder' on Dropbox, select the .apk file and it will install. Your done! :)
  - If you choose not to use the Cincom MANTIS Dropbox shared folder, continue with...
  - NOTE: you must download and install Dropbox on your computer too.
  - Then download the .apk file to your computer.
  - Put the .apk file into your DropBox folder.  
  - On your Android tablet, use the DropBox app and navigate to the .apk file.
  - Select the .apk file and it will install.

How to install the examples into MantisStudio
---------------------------------------------

* Download the .CMAR archive file
  - SourceForge will change the extention to .zip, i.e., <filename>.zip
  - Once downloaded, rename the file back to <filename>.CMAR 
  
* Within MantisStudio, import the .CMAR archive file
  - Select File->Import->Mantis->CMAR file, click Next
  - Browse to the .CMAR archive file
  - You can chose to import into an existing Mantis project, 'Into Mantis project' or
    check 'Use Web project name from within the archive file'
  - click Finish to import

How to access the Cincom Mantis CVS repository on sourceforge via MantisStudio
------------------------------------------------------------------------------

* Cincom Mantis CVS repository settings:
  - Host: cincommantis.cvs.sourceforge.net
  - Repository path: /cvsroot/cincommantis
  - User: anonymous
  - Password:
  - Connection type: pserver
  - Port: default

* Launch MantisStudio
* Open the CVS Perspective
  - Select Window->Open Perspective->Other->CVS Repository Exploring
* Add a new repository location
  - Select the "CVS Repository" tab and right-click anywhere in space below it
  - Select New->Repository Location...
  - Fill in the fields with the settings above
  - Select Finish

