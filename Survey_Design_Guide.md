<img src="./Files/LSHTM__ORK_logo.png" alt="drawing" width="400"/>
</Br>


### LSHTM Open Data Kit : ODK survey design guide

**version 2.0.0 -- 2018-10-17**

</Br></Br>

###Introduction

*This is not meant to be a definitive guide to designing ODK forms but should provide an overview of configuring your LSHTM Open Data Kit Server, devices and forms. More extensive documentation for ODK can be found at [docs.opendatakit.org](https://docs.opendatakit.org) and [xlsform.org](xlsform.org).  

More information about LSHTM Open Research Kits can be found on our project website [odk.lshtm.ac.uk](odk.lshtm.ac.uk)

#####Outcomes
At the end of this tutorial you should will be able to do the following.

	1. Design and build an ODK form in Microsoft Excel

Email queries to [*odk@lshtm.ac.uk*](mailto:ODK@LSHTM.AC.UK)
  
-

#### Overview

ODK forms are written in Microsoft Excel and are then converted to XML using a tool called [XLS Form Offline](https://github.com/opendatakit/xlsform-offline/releases/latest).  

More detailed instructions are available [here](xlsform.org).  

#### Instructions to create a blank XLS Form

* Create a new Excel worksheet (.xlsx) file
* Add three extra sheets and rename them (case sensitive) as 
	* ```survey```
	* ```choices```
	* ```settings```

The **survey** sheet includes the *questions* you will be asking.  
The **choices** sheet includes the possible *answers* to certain types of questions that appear in the survey sheet.  
The **settings** sheet includes the information needed for version control, form naming and data security.  

For each question we say
Type of Question
Name of Variable
Question +/- Explanation
Is the question mandatory to be completed
When should I ask this question (“skipping”)

