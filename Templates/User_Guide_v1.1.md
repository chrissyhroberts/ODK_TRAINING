<img style="float: right;" src="../Files/LSHTM__ORK_logo.png" alt="drawing" width="400"/>
</Br></Br></Br>

###LSHTM Open Data Kit : User Manual
**version 2.0.0 -- 2018-09-07**

*Compiled by Dr Chrissy h. Roberts & Dr Michael Marks*
</Br></Br>

###Introduction

*This is not meant to be a definitive guide to using ODK but provides an
overview of configuring your device to work with the LSHTM Open Data Kit Servers. More extensive documentation for ODK can be found at [docs.opendatakit.org](https://docs.opendatakit.org) and [xlsform.org](xlsform.org).


Email queries to [*odk@lshtm.ac.uk*](mailto:ODK@LSHTM.AC.UK)
  
-

####Setting up your server

1. 	**Request an ODK Server** at LSHTM by completing [this form](https://docs.google.com/forms/d/e/1FAIpQLSfz-dwv2knciYxO8651qja3MyQ6yCRhG8WjjDsBlediuNuozA/viewform]).  
 - You will receive a confirmation email which contains **the URL of your server**. This URL is only for use by your team and for the specific project named in the server request form.  
 - Usually servers are set up within 72 hours of request, but at busy times this may be longer.

2. **Access your server** using a browser (Chrome, Safari & Firefox have been tested)
 - The URL of your server will take the form ``` https://yourprojectname.odk.lshtm.ac.uk```  
3. **Login** in with the username ```admin``` and the password ```lshtm```. Note that these are case sensitive.  

4. **Set the admin password**
 - Select the ```Site Admin``` tab
 - By default there are two users setup: (A) ```admin``` & (B) ```anonymoususer```
 - Change the admin user password
 - Please note that password recovery for ODK servers is not a simple process. Pick a password that you can remember but which provides strong protection.  
 - A good technique for making passwords is to use four random words, put together in a memorable way
 - For instance ```grapes$CATCH$brickred$fudge``` is a strong and memorable password. 
 - Do not use simple replacement logic like this ```cl3v3r-pa55w0rd``` as passwords generated this way are easily cracked


5. **Disable** the rights of the ```Anonymoususer``` account
 - **You must disable Anonymoususer Form Manager -- Otherwise people can
access your data without a password**
 - Deselect the checkboxes to ensure that the ```Anonymoususer``` account does *not* have ```Data Viewer``` or ```Form Manager```rights. 
 - Unless you are running a **web-form** which will be filled anonymously, it is recommended that you deselect the ```Data Collector``` box for the ```Anonymoususer``` account. This will prevent anyone without a password from submitting data to your server.
 
6. Press the ```Save``` button to commit these changes

The new account can be created by

a\) Type a new username in the *Add Users* box and click *Add*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.56.07.png](media/image7.png)

b\) Give the new username *Data Collector* rights and set a password

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.59.54.png](media/image8.png)

c\) Save your changes

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
11.45.33.png](media/image6.png)

**YOUR ODK SERVER IS NOW SETUP AND SECURE**

**[SECTION 2: Uploading Blank Forms to the ODK Server]{.underline}**

**1)** You need to upload your *Blank forms* to the ODK Server.

A project might have more than 1 form (e.g First Visit, Second Visit
etc)

[This guide does not cover designing your forms]{.underline} - [
]{.underline} Links and guidance for writing forms are available at
[opendatakit.lshtm.ac.uk](opendatakit.lshtm.ac.uk)

**2)** Login to your server using the Admin Username and Password

Select the *Form Management* tab

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.26.09.png](media/image9.png){width="5.766666666666667in"
height="0.9777777777777777in"}

**3)** Click Add New Form

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.26.09.png](media/image9.png){width="5.763888888888889in"
height="0.9773064304461943in"}

**4)** Select the location of your ODK Form File and Click *Upload
Form*![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.31.58.png](media/image10.png){width="3.4944444444444445in"
height="2.050793963254593in"}

**5)** Repeat as needed. All of the uploaded forms will be displayed on
this page.

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.40.58.png](media/image11.png){width="5.7555555555555555in"
height="0.4222222222222222in"}

Remember if you update a survey form that you might need to delete old
versions of it from the server.

**YOUR FORMS ARE NOW AVAILABLE TO BE SYNCED TO DEVICES AND FOR DATA TO
BE UPLOADED**

**[SECTION 3: Setting up devices using ODK Collect and the LSHTM
Server]{.underline}**

**1)** Open ODK Collect on your smart phone/tablet and access *General
Settings*

![](media/image12.png){width="2.3602799650043744in"
height="4.2027777777777775in"}

**2)** Select *Configure Platform Settings *

![](media/image13.png){width="1.7670669291338583in"
height="3.138312554680665in"}

**3)** Enter the URL of your ODK Server **--** Make sure you include the
https://

e.g <https://example.odk.lshtm.ac.uk>

*The https (not http) is very important as that makes it a secure
connection*

![](media/image14.png){width="4.6194444444444445in"
height="3.2742465004374455in"}

**4)** [OPTIONAL BUT RECOMMENDED]{.underline}

If you have setup a Data Collector account with a username and password
(See Section 2 Above) also enter these now.

**5)** Return to the main screen and click *Get Blank Forms*

This will bring up a list of all the forms on your ODK server. Select
the ones you want and click *Get Selected.*

![](media/image15.png){width="1.4271489501312336in"
height="2.3805555555555555in"}
![](media/image16.png){width="1.5809864391951005in"
height="2.3895833333333334in"}

**YOUR SMART DEVICE IS NOW SETUP TO COLLECT DATA**

**[SECTION 4: Collecting and Uploading Data]{.underline}**

*Collecting Data (Steps 1-3) does not require a mobile or Wi-Fi
connection. Uploading data (Steps 4-5) requires a data connection.*

**1)** From the front screen select *Fill Blank Form*

![Screen Shot 2015-08-25 at
16.26.20.png](media/image17.png){width="1.180919728783902in"
height="2.013888888888889in"}

**2)** Select the appropriate Survey Form from the list

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.58.08.png](media/image18.png){width="2.8694444444444445in"
height="1.279957349081365in"}

**3)** Complete the Survey

**4)** On the final screen select *Save Form and Exit*

![](media/image19.png){width="1.4944444444444445in"
height="2.4815999562554683in"}

**5)** Select *Send Finalized Form*

![Screen Shot 2015-08-25 at
16.26.20.png](media/image17.png){width="1.693066491688539in"
height="2.887282370953631in"}

**5)** Select *Toggle All* then click *Send Selected* -- Data will now
be uploaded to your server

![](media/image20.png){width="2.3333333333333335in"
height="4.166666666666667in"}

**[SECTION 5: Exporting Data -- Basic CSV Files Only]{.underline}**

**If your data contains Nested Repeat Groups or Media Files please go to
Section 6**

**1)** Login to your ODK server

**2)** Uploaded data will be displayed for the currently selected form.

**3)** Select the *Form* you want to export ![Macintosh
HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.01.25.png](media/image21.png){width="5.7444444444444445in"
height="0.9111111111111111in"}

**4)** Click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.50.35.png](media/image2.png){width="5.7444444444444445in"
height="1.3333333333333333in"}

**5)** It will list the data that is being exported. Normally this will
be a CSV. Click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.02.28.png](media/image22.png){width="5.7555555555555555in"
height="1.3in"}

**6)** You will be taken to the *Exported Submissions* tab. This will
list the time and date of all exported data. Select the Dataset you want
to download the full dataset as a CSV

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.06.31.png](media/image23.png){width="5.7555555555555555in"
height="1.5333333333333334in"}

**[\
]{.underline}**

**[SECTION 6: Export Data -- Complex Datasets]{.underline}**

*If your survey includes repeated group questions or large amounts of
media associated with surveys you should use the [ODK Briefcase
package](https://opendatakit.org/downloads/download-category/briefcase/)
to download the survey*

**1)** Select *Pull data from* Aggregate 1.0 and click the *Connect*
button

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.34.55.png](media/image24.png){width="3.3694444444444445in"
height="2.953141951006124in"}

**2)** Enter the URL of your server and enter the username and password
of an account with Form Viewer and Data Manager rights (e.g the Admin
account).

Click *Connect.*

**URL BOX:** If your servers is called ABC.odk.lshtm.ac.uk then you need
to enter

https://ABC.odk.lshtm.ac.uk/ABC

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.35.03.png](media/image25.png){width="5.766666666666667in"
height="3.033333333333333in"}

**3)** ODK Briefcase will list all of the Survey forms available on the
server. Select the ones you want to download and click *Pull*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.34.55.png](media/image24.png){width="3.3694444444444445in"
height="2.953141951006124in"}

**4)** Switch to the *Export Tab.* Select the form you want to download
and set an export directory then click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.38.42.png](media/image26.png){width="3.3694444444444445in"
height="2.914991251093613in"}

**5)** ODK Briefcase will download the survey for you.

-   The main survey data will be downloaded in to a single CSV.

-   Nested repeats will be downloaded into a separate CSV -- these can
    be linked in a statistical package of your choice.

-   Media files will be downloaded into a folder with a linking
    identifier.

-   If you have collected data using OpenMapKit the OSM files will be in
    the Media Folder
