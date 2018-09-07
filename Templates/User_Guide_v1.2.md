![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.50.49.png](media/image1.png)

User Manual

Version 1.1 -- 9^th^ March 2016

**Dr Chrissy h. Roberts**

**Dr Michael Marks**

[**ODK\@LSHTM.AC.UK**](mailto:ODK@LSHTM.AC.UK)

[**OPENDATAKIT.LSHTM.AC.UK**](opendatakit.lshtm.ac.uk)

**[Setting up and Using ODK @ LSHTM]{.underline}**

*This is not meant to be a definitive guide to using ODK but provides an
overview of configuring your device to work with the ODK\@LSHTM Server
Setup.*

[Requesting an ODK Server at LSHTM]{.underline}

-   Complete the Server Request form at
    [opendatakit.lshtm.ac.uk](https://opendatakit.lshtm.ac.uk/files/2015/09/LSHTM-ODK-Server-%E2%80%93-Project-Request.docx)

-   Email the form to [mailto:ODK\@lshtm.ac.uk](mailto:ODK@lshtm.ac.uk)

[If you have used ODK and Aggregate Servers before]{.underline}

-   Sections 1 and 3 provide specific details for setting up your ODK @
    LSHTM Server

[If you have not used ODK or an Aggregate Server before]{.underline}

-   Sections 1 and 2 provide details for setting up your server and
    uploading blank survey forms

-   Sections 3 and 4 provide details for downloading blank forms to
    smartphones/tablets, collecting data and uploading completed surveys
    to the server

-   Section 5 provides details for downloading completed data from the
    server

[Advanced Users: Nested Repeats and Media File Downloads]{.underline}

-   Section 6 provides details for using ODK Briefcase for downloading
    nested repeats and media files associated with your survey

**[SECTION 1: Setting up your ODK Aggregate Server]{.underline}**

**Please follow the instructions below on [First Login]{.underline} --
this is essential to ensure the full security of your data**

**1)** Your project will be accessed at:

example.odk.lshtm.ac.uk

**2)** Click *Log In*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.50.35.png](media/image2.png)

**3)**Select *Sign in with Aggregate password*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.56.42.png](media/image3.png)

The default account details are:

Username: admin

Password: lshtm

**4)** The *Site Admin* tab will now appear

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.59.16.png](media/image4.png)

**5)** Select the *Site Admin* tab

By default there are two users setup:

1\) admin 2) anonymoususer

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.00.54.png](media/image5.png)

**6)** [CHANGE]{.underline} admin Password

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.00.54.png](media/image5.png)

**7)** [DISABLE]{.underline} Anonymoususer Form Manager

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.00.54.png](media/image5.png)

*You must disable Anonymoususer Form Manager -- Otherwise people can
access your data without a password!*

**8)** [SAVE]{.underline} your changes

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
11.45.33.png](media/image6.png)

**8)** [OPTIONAL BUT RECOMMENDED]{.underline}

We strongly recommend you also disable *Data Collector* for Anonymous
Users and create a password protected account with *Data Collector*
rights

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
[opendatakit.lshtm.ac.uk](opendatakit.lshtm.ac.uk){.uri}

**2)** Login to your server using the Admin Username and Password

Select the *Form Management* tab

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.26.09.png](media/image9.png)

**3)** Click Add New Form

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.26.09.png](media/image9.png)

**4)** Select the location of your ODK Form File and Click *Upload
Form*![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.31.58.png](media/image10.png)

**5)** Repeat as needed. All of the uploaded forms will be displayed on
this page.

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
21.40.58.png](media/image11.png)

Remember if you update a survey form that you might need to delete old
versions of it from the server.

**YOUR FORMS ARE NOW AVAILABLE TO BE SYNCED TO DEVICES AND FOR DATA TO
BE UPLOADED**

**[SECTION 3: Setting up devices using ODK Collect and the LSHTM
Server]{.underline}**

**1)** Open ODK Collect on your smart phone/tablet and access *General
Settings*

![](media/image12.png)

**2)** Select *Configure Platform Settings*

![](media/image13.png)

**3)** Enter the URL of your ODK Server **--** Make sure you include the
https://

e.g <https://example.odk.lshtm.ac.uk>

*The https (not http) is very important as that makes it a secure
connection*

![](media/image14.png)

**4)** [OPTIONAL BUT RECOMMENDED]{.underline}

If you have setup a Data Collector account with a username and password
(See Section 2 Above) also enter these now.

**5)** Return to the main screen and click *Get Blank Forms*

This will bring up a list of all the forms on your ODK server. Select
the ones you want and click *Get Selected.*

![](media/image15.png) ![](media/image16.png)

**YOUR SMART DEVICE IS NOW SETUP TO COLLECT DATA**

**[SECTION 4: Collecting and Uploading Data]{.underline}**

*Collecting Data (Steps 1-3) does not require a mobile or Wi-Fi
connection. Uploading data (Steps 4-5) requires a data connection.*

**1)** From the front screen select *Fill Blank Form*

![Screen Shot 2015-08-25 at 16.26.20.png](media/image17.png)

**2)** Select the appropriate Survey Form from the list

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.58.08.png](media/image18.png)

**3)** Complete the Survey

**4)** On the final screen select *Save Form and Exit*

![](media/image19.png)

**5)** Select *Send Finalized Form*

![Screen Shot 2015-08-25 at 16.26.20.png](media/image17.png)

**5)** Select *Toggle All* then click *Send Selected* -- Data will now
be uploaded to your server

![](media/image20.png)

**[SECTION 5: Exporting Data -- Basic CSV Files Only]{.underline}**

**If your data contains Nested Repeat Groups or Media Files please go to
Section 6**

**1)** Login to your ODK server

**2)** Uploaded data will be displayed for the currently selected form.

**3)** Select the *Form* you want to export ![Macintosh
HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.01.25.png](media/image21.png)

**4)** Click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-12 at
20.50.35.png](media/image2.png)

**5)** It will list the data that is being exported. Normally this will
be a CSV. Click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.02.28.png](media/image22.png)

**6)** You will be taken to the *Exported Submissions* tab. This will
list the time and date of all exported data. Select the Dataset you want
to download the full dataset as a CSV

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
10.06.31.png](media/image23.png)

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
09.34.55.png](media/image24.png)

**2)** Enter the URL of your server and enter the username and password
of an account with Form Viewer and Data Manager rights (e.g the Admin
account).

Click *Connect.*

**URL BOX:** If your servers is called ABC.odk.lshtm.ac.uk then you need
to enter

https://ABC.odk.lshtm.ac.uk/ABC

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.35.03.png](media/image25.png)

**3)** ODK Briefcase will list all of the Survey forms available on the
server. Select the ones you want to download and click *Pull*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.34.55.png](media/image24.png)

**4)** Switch to the *Export Tab.* Select the form you want to download
and set an export directory then click *Export*

![Macintosh HD:Users:Michael:Desktop:Screen Shot 2015-10-13 at
09.38.42.png](media/image26.png)

**5)** ODK Briefcase will download the survey for you.

-   The main survey data will be downloaded in to a single CSV.

-   Nested repeats will be downloaded into a separate CSV -- these can
    be linked in a statistical package of your choice.

-   Media files will be downloaded into a folder with a linking
    identifier.

-   If you have collected data using OpenMapKit the OSM files will be in
    the Media Folder
