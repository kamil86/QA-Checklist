
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

<img src="images/2023-02-06_10-33-18.png" alt= “” width="600" height="300">
 
 - each object has its own lifecycle as it was implemented as case type
 
 - possibility to customize checklist questions
 
 <img src="https://github.com/kamiljaneczek/QA-Checklist/blob/d3f4ca1c8d0970114cdb341c0254e36a64e0d624/images/2023-02-06_10-01-58.png" alt= “” width="370" height="340">


 <img src="images/2023-02-06_10-03-58.PNG" alt= “” width="550" height="550">

 
 - possibility to customize approval workflow (who needs to approve checklist)
 
  <img src="/images/2023-02-06_10-31-21.png" alt= “” width="210" height="180">

 
 - It is possible to assign this configuration per project

 <img src="/images/2023-02-06_10-32-00.png" alt= “” width="180" height="120">
 
 - Create checklist with detailed information

 <img src="/images/2023-02-06_10-34-38.png" alt= “” width="420" height="370">

 <img src="/images/2023-02-06_10-35-14.png" alt= “” width="420" height="610">
 
 - generate PDF with all relevant information (checklist questions with answers and approval details).

 <img src="/images/2023-02-06_10-40-21.png" alt= “” width="850" height="550">
 

Genereted PDF includes full logs of approvals and can server as formal document delived to customer after each of sprint.
