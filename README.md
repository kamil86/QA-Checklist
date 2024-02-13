
# QA Checklist

## Bussiness value

Quality Checklist is an application initially written in Pega 7.4 and later upgraded to newest platform version (Pega 8.8.1 as of February 2021). 

Main goal of this application is to **improve quality of development** using Pega platform.

Application tracks formal documentation of quality measures taken during and after developing user story and before handing it over to testing team. Application allows to configure Quality checklist form (per project) and customizes approval workflow (who needs to approve checklist).

## Installation

In you Pega 8 environment navigate to Confgure -> Application -> Distribution -> Import and select zipped RAP file avialable in this repository. After sucessfull import of application add one of following Access Groups to your operartor: QAChecklist:Admin, NHChecklist:LSA or NHChecklist:Dev.

Switch to **QA Checklist** application.

## Manual

Main application features include:

 - ability o setup project structure (project with releases and sprints)
![Alt Text](images/2023-02-06_10-33-18.png)

 - each object has its own lifecycle as it was implemented as case type
 
 - possibility to customize checklist questions
 ![Alt Text](images/2023-02-06_10-01-58.png)
 ![Alt Text](images/2023-02-06_10-03-58.png)

 - possibility to customize approval workflow (who needs to approve checklist)
 
 
 ![Alt Text](images/2023-02-06_10-31-21.png)

 
 - It is possible to assign this configuration per project
 ![Alt Text](images/2023-02-06_10-32-00.png)

 - Create checklist with detailed information
![Alt Text](images/2023-02-06_10-34-38.png)

![Alt Text](images/2023-02-06_10-35-14.pn)
 
 - generate PDF with all relevant information (checklist questions with answers and approval details).

![Alt Text](images/2023-02-06_10-40-21.png)


Genereted PDF includes full logs of approvals and can server as formal document delived to customer after each of sprint.
