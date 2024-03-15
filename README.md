# The Power Platform BPM Toolkit 2023 (Dataverse version, early alpha version)

the solution file is here: [https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPMToolkit_DataverseAlphaFebruary2024.zip]

1. There is a new workflow engine (100% implemented with Power Automate)
2. The data model is new:

<a href="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%20-%20Dataverse%20Data%20Model.png"> <img src=https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%20-%20Dataverse%20Data%20Model.png width="760" height="420"> </a>

3. The code has been re-written from scratch
4. The security model is not implemented yet
5. The error handling must be generalized
6. The setup guide will be uploaded soon


 To evaluate the BPM Toolkit, or to use it in production, download and install the version SharePoint.
 We will upload the final Dataverse version in September 2023.

# The Power Platform BPM Toolkit 2022 (SharePoint version)

Welcome to the 2022 release of the Power Platform BPM Toolkit for SharePoint.  
The creator of this tool is Serge Luca aka 'Doctor Flow'.  
@sergeluca. 


### What is the BPM Toolkit ?  

BPM means "Business Process Management".


[BPM in Wikipedia](https://en.wikipedia.org/wiki/Business_process_management).   
[BPM according to IBM](https://www.ibm.com/cloud/automation-software/business-process-management). 

The goal was to provide a highly secured approval system that can be used in HR, supply chain management, finance in order to fix some shortcomings in the Power Platform like the 30 days approval limitation, no tasks delegation, no state machine, no graphical view of the running workflows,...  


<img src="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%20facts.jpg" width="760" height="420">

### New features in the 2022 version

1. Improved and faster state machine engine.
2. Improved UX.
3. Improved reliability
4. Batch approval
5. BPM Toolkit monitoring application
6. BPM Toolkit archiving application
7. New workflow verbs
8. Improved goto verbs
9. Environment variables
10. Ping me
11. Refactoring
12. 67 bugs fixed

### What is still missing

Automatic task delegation works, but expiration doesn't work anymore regression to fix
Power BI report with role level security (ongoing).

### Videos describing the BPM Toolkit features and architecture

This video still illustrates the previous version (2021); a new & updated video is coming soon.

<a href="https://www.youtube.com/watch?v=QJS_6Ds1owo&t=2197s"> <img src=https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/bpmtoolkitvideofeature.png width="760" height="420"> </a>


<a href="https://www.youtube.com/watch?v=8_uj-mNA4XE&t=196s"><img src=https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/bpmtoolkitvideoarchitecture.png width="760" height="420">
</a>


### How can I start using the BPM Toolkit ?

1.Install the BPM Toolkit (see next paragraph).  
2.Follow the BPM Toolkit using guide to create your own request compatible with the BPM Toolkit. 

### How can I install the BPM Toolkit ?

<a href="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%202022%20setup%20guide.pdf"><img src="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPMToolkit2022Setup.jpg" width="760" height="420"></a>
  
To install this preview, you will need the following files:  


1. the [setup guide (pdf)](https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%202022%20setup%20guide.pdf).
2. the [setup files](https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPMToolkit_2022_setup.zip). 

### Install and configure the Demo application and start using the BPM Toolkit

<a href="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%202022%20using%20guide.pdf"><img src="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPMToolkit2022Using.jpg" width="760" height="420"></a>

Just follow the [BPM Toolkit Using guide (pdf)](https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%202022%20using%20guide.pdf).

### How can I create my own custom request compatible with the BPM Toolkit ? 

a Developer's guide is coming soon.

### BPM Toolkit Architecture

A new video is coming to illustrate the following architecture:

<img src="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/BPM%20Toolkit%20modules.jpg" width="760" height="420">

### The vision

The Business process mining and the analytics must still be created.
The Dataverse version is already there, but in early beta version.

<img src="https://github.com/sergeluca/Power-Platform-BPM-Toolkit/blob/main/bpm%20toolkit%20vision.jpg" width="760" height="420">


### License needed for using the Power Platform BPM Toolkit (SharePoint)

The end users only need a normal Office 365 license. 
IT needs a premium license for the deployment. 
If you create custom actions, you will need the Per flow license (500$/month for the whole company)
If you want a RPA interaction, you will need the Per Flow license + 1 RPA license

### Why do I need to use SharePoint ?

Because your end users don't have to pay a premium license to benefit from all features provided by the BPM Toolkit. 
We are working on a CDS/Dataverse version that will require a premium license. 

### Is the BPM Toolkit used by real companies ?

yes, several multinational companies are using the BPM Toolkit for automating their HR business process. They are currently testing the tool.

Doctor Flow aka "Serge Luca"
