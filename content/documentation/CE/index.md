---
title: "Archiving and Recovery"
weight: 20
type: docs
description: >
    Archiving and Recovery on CE.
---

![](./images/)



| <br>EXIMBILLS © Trade Finance System<br><br>Customer Enterprise Version 3\.3\.6<br><br>Archiving and Recovery<br><br>July 2021                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| *Copyright* *2021* *© China Systems Corporation*<br><br>*All Rights Reserved*<br><br><br><br>*This document is protected by United States Copyright Law and may contain Trade Secrets Information which is proprietary to China Systems Corporation\.  No part of this document may be copied, photocopied, reproduced, translated, distributed, or reduced to any electronic medium or machine\-readable form without prior consent in writing from China Systems Corporation\.  The information in this document may be used only under the terms and conditions of separate China Systems Corporation license agreements\.*<br><br>*Information is subject to change without notice\.  China Systems Corporation makes no warranties, either expressed or implied, with respect to the software herein described as to its quality, performance, including, without limitations to, its fitness for any particular purpose\.*<br><br>*This document may not reflect total system capability at any subsequent date as a result of development\.  It is also possible that it may contain references to facilities not available on your computer system\.  Such references should not be construed to mean that these facilities will necessarily be made available on all types of computer hardware or in all user locations\.*<br><br>*China Systems Corporation accepts no responsibility or liability for any damages or loss of business or revenue due to the use of this document\.*<br><br>*All trademarks, registered trademarks and trade names mentioned in this document are the sole property of their respective holders\.* |
| ORDER MORE EXIMBILLS DOCUMENTATION<br><br>Additional copies of Documentation are available for purchase from China Systems Corporation or through your local EXIMBILLS Support Office\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ![csliit](./images/35930536-7cd8-4bbc-a37b-85d17c45ebc5.jpeg)<br><br>CHINA SYSTEMS CORPORATION<br><br>Comments may be addressed to:<br><br><u><span style="color:#0000FF">[corporatedocs@chinasystems\.com](mailto:corporatedocs@chinasystems.com)</span></u><br><br>China Systems Corporation Ltd\.<br><br>Corner House, 20 Parliament Street<br><br>Hamilton HM12<br><br>Bermuda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |



Table of Contents

[CE Documentation Library](<error reading>)

[CE Documentation Library](<error reading>)

[Core System Manuals](<error reading>)

[CE Utility Reference Manuals](<error reading>)

[Installation Guides](<error reading>)

[Introduction](<error reading>)

[System Overview](<error reading>)

[Manual Overview](<error reading>)

[Using the CE Utility](<error reading>)

[Running the CE Utility](<error reading>)

[Preparing the CE Utility Files](<error reading>)

[Accessing the CE Utility](<error reading>)

[Navigating the CE Utility Interface](<error reading>)

[Generating the XML Parameter Files](<error reading>)

[Building a Product](<error reading>)

[Archiving Prerequisites](<error reading>)

[Archiving / Backup Database Settings](<error reading>)

[Data Source Settings](<error reading>)

[WebSphere Data Source Settings](<error reading>)

[CE Utility Data Source Settings](<error reading>)

[Log Settings](<error reading>)

[Manual Archive Mode](<error reading>)

[Overview](<error reading>)

[Common Parameter Settings](<error reading>)

[Archive Control Component](<error reading>)

[Archive Product Items](<error reading>)

[Error Codes](<error reading>)

[JSP and JS Settings](<error reading>)

[Archive Data Function](<error reading>)

[Parameter Settings](<error reading>)

[Transaction Process](<error reading>)

[Restore Archived Data Function](<error reading>)

[Parameter Settings](<error reading>)

[Transaction Process](<error reading>)

[Inquire Archived Data Function](<error reading>)

[Parameter Settings](<error reading>)

[Transaction Process](<error reading>)

[Auto Archive Mode](<error reading>)

[Overview](<error reading>)

[Parameter Settings](<error reading>)

[Transaction Process](<error reading>)

[Archiving through STP](<error reading>)

[Overview](<error reading>)

[Parameter Settings](<error reading>)

[Transaction Process](<error reading>)

[Sample Archiving JSP and JS Files](<error reading>)

[IMLC\_ArchiveCriteria\.jsp](<error reading>)

[IMLC\_ViewArchive\.jsp](<error reading>)

[IMLC\_ViewArchive\_Function\.JS](<error reading>)

[IMLC\_ViewArchive\_Event\.JS](<error reading>)

[Glossary](<error reading>)

[Glossary](<error reading>)





CE Documentation Library



CE Documentation Library

The CE Documentation Library lists all available manuals that serve as references on the use of the Customer Enterprise system\. The documents are categorized into three groups: Core System Manuals, CE Utility Reference Manuals, and Installation Guides\.





Core System Manuals

The CE core system manuals provide details on the setup and configuration of various CE parameters, as well as the implementation of supplementary functionalities supported by the system\.





Archiving and Recovery

This manual is a reference to the Archive and Recovery functionality of the CE system\. Discussions include the required parameter settings for configuring the relevant functions, as well as examples of how this functionality is used in transaction processes\.





Building a Product

This manual is a reference to the process of building a product in CE\.  It provides step\-by\-step procedures on how to create a basic CE module, transaction function, and product setting; configure parameters; and attach components to generate a working business product\.



Data Objects

This manual serves as a reference for creating and utilizing data objects in the CE system\.  The discussions provide details on how to build data object templates and data object entities, and how to attach these to the transaction function screen\.



Frequently Asked Questions

This document addresses commonly\-asked questions on the Customer Enterprise system\.  Issues on the browser\-side \(transaction processing\), CE Utility, Security Module, and database, among others, are addressed in the discussions\.





Interfacing CE with CS Eximbills

This document discusses the process of interfacing CE with the CS Eximbills \(CSX\) back office system\. Employing the MQ, FTP, and TCP/IP communication protocols, the interface process using the XML format is detailed in this document\.



Interfacing CE with Eximbills Enterprise

This document discusses the process of interfacing CE with the Eximbills Enterprise \(EE\) back office system\.  Employing the MQ protocol, the interface process for the transfer of data between CE and EE using the XML format is detailed in this document\.



Log Settings

This manual provides details on CE logs as well as general instructions on log configuration in CE\.  This is especially written for the users who are in charge of maintaining the CE system\.



Look and Feel

This manual is a reference guide on designing the CE user interface \(i\.e\., the look and feel of the system\)\.  Divided into two parts, the manual provides instructions on creating a\) the basic L&F style of CE; and b\) the CE L&F style that incorporates widgets\.



Multi\-Entity

This manual is a reference on implementing the Multi\-Entity functionality of the CE system\.  Discussions cover the implementation and application of CE multi\-entity\.



Multi\-Language

This manual discusses the procedures required in setting up the Multi\-Language functionality of CE as it is run by Administrator\- and Operator\-type users\. Furthermore, the configuration of certain system and browser elements as well as the setup of related system parameters is explained in step\-by\-step procedures\.



Reports

This manual is a comprehensive reference guide on the requirements and processes involved in building business products and functions that generate online reports and documents\.





Security and System Maintenance Functions

This manual is a comprehensive guide on the security and system maintenance of the CE system\.  As such, it includes detailed instructions for company and company function management, and user and user function management\.  Maintenance of key functionalities such as authorization rules, reference numbers, and other services is covered as well\. In addition, this document discusses the security concepts in CE to assist users assigned with access rights to the CE Security Module\.



Standing Data Functions

This document discusses the functions for the CE standing data that are maintained by operators \(e\.g\., parties, clauses\)\.  It includes sections for each function, starting with a brief description of the function, followed by the function input when necessary, and the procedure steps\.



Supplementary Functions

This manual is a reference for the CE Utility operator user in configuring parameter, JSP, and transaction function settings to define special or supplementary CE functionalities such as uploading images; sending images and forms to the back\-office system; and sending notifications via e\-mail, SMS, and widgets\.



System Administration Functions

This manual is a reference for the default Super Administrator user of the CE Utility in the configuration and maintenance of the CE environment\.  It discusses in detail user management and parameter management\.



System Reference

This document serves as a quick reference to the following elements that are used when configuring specific parameters in the CE Utility: global system parameters, system parameters, components, XML Generator items, server side system methods, system JS methods, and APIs\.



CE Utility Reference Manuals

The CE Utility Reference set of manuals is a guide on the use of the Customer Enterprise Utility Workbench, or simply CE Utility\.  This reference provides details on every function or feature in the CE Utility and includes instructions and step\-by\-step procedures on how to operate or use the function in relation to operating and maintaining the CE system and processing a business transaction\.

A manual is provided for each function group of the CE Utility: 

*CE Utility* *Reference:* *User Manager Functions*, for the functions that belong to the User Manage function group of the CE Utility when accessed by an Administrator or Operator user

*CE Utility* *Reference:* *Parameter Manager Functions*, for the functions that belong to the Parameter Manage function group of the CE Utility when accessed by an Administrator or Operator user

*CE Utility* *Reference:* *System Functions*, for the functions that belong to the System Function group of the CE Utility\.

*CE Utility* *Reference:* *Transaction Functions*, for the functions that belong to the Transaction Function group of the CE Utility\.

*CE Utility* *Reference:* *Product Functions*, for the functions that belong to the Product Function group of the CE Utility\.

*CE Utility* *Reference:* *Maintenance Functions*, for the functions that belong to the Maintenance function group of the CE Utility\.







Installation Guides

The CE installation guides are references on the installation and setup processes of the CE system on different application servers and databases\.





**Installation Guide WAS** **9** **\- Oracle** **19c**

This is a reference for installing the CE system on WebSphere Application Server Version 9\.0\.5\.6, with an Oracle 19c database\.  This includes detailed instructions on configuring the components that are required to successfully run CE\.







Introduction

System Overview

Manual Overview



System Overview

Transactions that are old, completed, or canceled consume much disk space that is better used to store future records\.  Moreover, this slows down transaction processes\.  While these types of records can simply be deleted, there is no way to retrieve them for inquiry or any subsequent process\. 

The Archiving and Recovery functionality of CE addresses these setbacks\. Archiving is the process of transferring transaction records from the Transaction Database to the Backup Database\. Recovery, on the other hand, is the process of retrieving archived records from the Backup Database\. Recovered records may be used for other operations or inquiry, depending on the bank's requirements\.

Archived data include master file transaction data and the associated data such as documents, images, GAPI, e\-mails, and forms\.

Run by bank operators, the Archiving functions in CE can only be created for transaction modules\.  These functions are Archive Data, Inquire Archived Data, and Restore Archived Data\. 

There are two modes of archiving:

Manual Archiving, in which records are manually archived per module according to a set of defined criteria\.  In addition, records received via STP can also be archived through this mode\.

Auto Archiving, in which records are automatically archived by batch according to a set of defined criteria\. This is also called Batch Archiving\.



Creating Archiving functions requires specific installation, database, and parameter settings\.









Manual Overview





<u>**Purpose**</u>

This manual is a reference to the Archive and Recovery functionality of the CE system\. Discussions include the required parameter settings for configuring the relevant functions, as well as examples on how this functionality is used in transaction processes\. 

The archiving functions discussed in this document are manual Archiving functions \(Archive Data, Restore Archived Data, and Inquire Archived Data\), Batch Archive function, and STP Archive function\.



<u>**Audience**</u>

This document is written specifically for, but not limited to, the following users: 

Consultants tasked to implement the Archive and Recovery functions in a business module\.  These users must have sufficient knowledge of running CE Utility functions, building a product, and installing the CE system\.

Bank or browser\-side users in charge of processing, managing, and maintaining transaction records\.



<u>**Prerequisites**</u>

Sufficient knowledge of building business products is required\. Recommended titles before reading this manual are as follows:

*CE* *Building a* *Product*

*C**E Installation Guide*

*C**E System Administration Functions*

*CE Utility References*







![Tzone55](./images/680d2efe-5635-48b7-b50f-de19368b58b4.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">Some features discussed in this manual have been tested and documented based on an older system version\.  Unless otherwise specified, the overall functionality is the same when recreated in the current version\.</span>





Using the CE Utility

Running the CE Utility

Generating the XML Parameters

BUILDING A PRODUCT









Running the CE Utility

The Customer Enterprise Utility Workbench, or CE Utility, is the main tool for building parameters in CE\.





Preparing the CE Utility Files

Along with the installation files, the CE Utility folder is provided with every CE system release\. Prior to using the CE Utility, do the following:

Copy the CE Utility folder to the local drive\.

Define the required environment variables\.

Map the CE directories \(e\.g\., CEWeb\.war and CE\_PARA\) to the network drive\.





| ![](./images/5b77645f-1fe2-4b1d-9dc3-8b3cf7a35bce.jpg) |
| :-----------------------------------------------------------: |

***Figure 2\.*** ***1*** ***CE Utility Folder***



![Tzone55](./images/949d063e-2dfe-403e-88d3-7d580ac6aa65.jpeg)<span style="color:#008080">**NOTE:**</span> 

<span style="color:#008080">The default drives defined in the GEN\_XML\_ROOTPATH and GEN\_WEB\_ROOTPATH system parameters are</span> <span style="color:#008080">O:\</span> <span style="color:#008080">and</span> <span style="color:#008080">P:\</span> <span style="color:#008080">respectively\. These drives, if currently not existing, may be created through a batch file\. While</span> <span style="color:#008080">O:\</span> <span style="color:#008080">and</span> <span style="color:#008080">P:\</span><span style="color:#008080">are the default drives for CE, these may be set to any other preferred drive available in the network\.</span> 

<span style="color:#008080">To enable users to use the CE Utility on their own local machines as clients connecting to the CE server: 1\) Install the Java Development Kit \(JDK\) program; 2\) Copy the CE Utility folder; 3\) Create the</span> <span style="color:#008080">JAVA\_HOME</span> <span style="color:#008080">environment variable, which</span> <span style="color:#008080">must</span> <span style="color:#008080">point to this directory:</span> <span style="color:#008080">\[Java Home\]\\[Installed JDK\]</span><span style="color:#008080">\.</span>

<span style="color:#008080">For more information on setting up the CE environment, refer to the CE installation guides</span><span style="color:#008080">*\.*</span> 

<span style="color:#008080">For information on the CE Utility functions, refer to the</span> <span style="color:#008080">*CE Utility Reference*</span> <span style="color:#008080">manuals\.</span>





| **Batch File for Creating the CE Drives**<br><br>The batch file for creating drives contains the following commands:<br><br><br><br>subst O: /d<br><br>subst P: /d<br><br>subst O: C:"\Program Files\IBM\WebSphere\AppServer\profiles\AppSrv01\installedApps\DOCS\-CEV336Node01Cell\CE\.ear\CE\_PARA"<br><br>subst P: C:"\Program Files\IBM\WebSphere\AppServer\profiles\AppSrv01\installedApps\DOCS\-CEV336Node01Cell\CE\.ear\CEWeb\.war" <br><br><br><br>![](./images/57ae46a7-5984-4918-998d-c60785b5e940.jpg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |



Accessing the CE Utility

The main program for running the CE Utility is the CEUtility\.bat file, which is found in the CE Utility folder\.



| <span style="color:#000000">**Do the following \. \.**</span> <span style="color:#000000">**\.**</span> |
| ------------------------------------------------------------------------------------------------------- |



| Run the CEUtility batch program to access the CE Utility\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">A shortcut for the CEUtility batch file can be created on the desktop for easy access\.</span>                                                                                                                                                                                                                                                                                                                                                         |      | ![](./images/f0de4057-32cb-4475-912f-0b2089a6765c.jpg) |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| The logon window of the CE Utility is displayed\.<br><br>To define the database information, click on the Profile button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![](./images/91c27a4f-c005-49dc-989f-3ebe873ffc7b.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| In the Database Information dialog box that is displayed, specify the required database details and click on the Save button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](./images/ef5843c0-1c3e-4aff-a993-022b20c8f1f1.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| A confirmation message is displayed\. Click on the OK button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](./images/24ed2f38-f84e-457a-ba6c-383e5c738ce8.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">This new data source setting is saved in the</span> <span style="color:#008080">UserInfo\.xml</span> <span style="color:#008080">file in the CE Utility directory\.</span>                                                                                                                                                                                                                                                                                                                                                       |      | ![](./images/8a0daf95-8f9f-4ea2-940c-7647920ead56.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| The relevant username and password may then be specified for logging on the CE Utility\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">For information on defining CE Utility user profiles, refer to the</span> <span style="color:#008080">*CE System Administration Functions*</span> <span style="color:#008080">manual\.</span>                                                                                                                                                                                                                            |      | ![](./images/01df76d7-4990-4721-87e8-b647bf436a6a.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| The CE Utility window is displayed\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![](./images/65b18a7a-8d5b-4e2d-bd99-e57475158377.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                               |
| A function is accessed by opening or double\-clicking on the relevant function group and clicking on the function name\.<br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">A user may only access and utilize the functions assigned to him\.</span>  <span style="color:#008080">For more details, refer to the</span> <span style="color:#008080">*CE Utility Reference*</span><span style="color:#008080">*:*</span> <span style="color:#008080">*User Manager Functions*</span> <span style="color:#008080">documentation</span><span style="color:#008080">*\.*</span> |      | ![](./images/64308560-e899-4d85-9a2c-3d916b02136a.jpg) |



![Tzone55](./images/87b424bc-d215-4afd-a392-e4e63828663b.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">It is sometimes necessary to assign a new user name and password when the new database is restored from a backup file\.  Restoring the backup file restores the original user profiles\.</span>

<span style="color:#008080">The new user profiles for the CE Utility \(as well as the CE Security Module\) can be defined during the installation process\.  SQL scripts are run to create these profiles\.  Refer to the CE installation guides for more information\.</span>

Navigating the CE Utility Interface

After logging on, the CE Utility window is displayed and parameters may then be configured\. The functions used for setting up parameters may be accessed by clicking on the function name on the Function menu or by using the shortcut buttons\.

The CE Utility interface also provides ways by which parameters can be created, edited, deleted or linked to other operations: menu bar, toolbar buttons, and popup menu\.





| ![](./images/b0e776e3-1ac6-4b8a-8762-81751458b35f.jpg) |
| :-----------------------------------------------------------: |

***Figure 2\.*** ***2*** ***The CE Utility Interface***





![Tzone55](./images/048d1627-3390-4495-8bd7-9e3be9955800.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">A function is only displayed, and its corresponding button or menu option enabled, if the user has been given the right to access this function\.</span>  <span style="color:#008080">Some options and functions are only available to Super Administrator users, while others are only accessible to Administrator and Operator users\.</span>









CE Utility Functions

The functions that may be accessed for setting up parameters are organized together into several function groups\. The current available function groups and their corresponding functions in the CE Utility are as follows:





**User Manager Function Group**

This function group is comprised of functions used for creating, configuring, and exporting Bank\-Country group settings; creating new users; and configuring data sources\. These functions are:

Business Unit Config

DataSource Manage

Import/Export Business Unit

User Manage





**Parameter Manage Function Group**

This function group consists of functions used for maintaining system\-wide parameters and components\. These functions are:

AP Server

Component Manage

Language Configuration

System Parameter

System Parameters





**System Function Group**

This function group consists of functions used for maintaining and facilitating system\-wide tasks, operations, and settings\. These functions are:

Image Type Maintain

Output Device

Queue Manager

STP Setting

Time Zone





**Transaction Function Group**

This function group is comprised of functions used for defining the actual business parameters of transaction functions\.  These facilitate the maintenance and processes of the business transaction modules\. These functions are:

Amount/Rate Format

Batch Manage

Clause

DO Get Data

Export Setting

Form

GAPIs Setting

Get Data

Image Control

Message Broker Setting

Module & Event

Report Template

STPs Mapping

Sub Tasks

SWIFT Config

System Maintain

Transaction Function

Transfer To

TSU Mapping

Upload Message Setting

Web Service Setting

Widget Maintain





**Product Function Group**

This function group consists of functions that are used for creating and configuring the products to be accessed and used by the customers or end\-users\. These functions are:

Fields Select

Inbox

Product Authorize

Product Authorize Setting

Product Catalog

Product Function Setting

Product Item

**Maintenance Function Group**

This function group is comprised of functions used for facilitating the maintenance of data from CE tables, including fields and error settings\. These functions are:

DB Dictionary

Error Handling

Error Message Config \(CE\)

Field Conversion

Multi Language

Page Dictionary

XML Generator









Menu Bar

The options on the menu bar are shortcuts to both the common and specific functions and tasks of the system\.



| ![](./images/a011066d-2e0d-42b5-ab20-065b4ef8ddc3.jpg) |
| :-----------------------------------------------------------: |

***Figure 2\.*** ***3*** ***Menu Bar***





| <span style="color:#000000">**Menu**</span> |      | <span style="color:#000000">**Description**</span> |
| :-----------------------------------------: | :--: | :------------------------------------------------: |



| **File**     |      | The available options in the File menu are:<br><br>New: This is used for creating a new parameter or rule\.<br><br>Save: This is used for saving the created or modified settings\.<br><br>Close Function: This is used for closing the current function window\.<br><br>Connect To: This is used for connecting to another Meta data source\.<br><br>Log Off: This is used for logging off a user that is logged on to the system without exiting the system\.<br><br>Exit: This is used for closing the system window and exiting the system\.                                                                                                                                                  |
| -----------: | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              |      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Edit**     |      | The available options in the Edit menu are:<br><br>Add: This is used for adding a setting for the selected function or parameter\.<br><br>Delete: This is used for deleting or removing an existing setting\.<br><br>Edit: This is used for editing or modifying existing settings\.<br><br>Copy: This is used for copying or duplicating a selected setting\.<br><br>Find: This is used for finding a specific setting\.                                                                                                                                                                                                                                                                         |
|              |      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Function** |      | The available options in the Function menu are:<br><br>User Manage, which displays options for running User Manager functions<br><br>Parameter Manage, which displays options for running Parameter Manager functions<br><br>System Function, which displays options for running System functions<br><br>Transaction Function, which displays options for running Transaction functions<br><br>Product Function, which displays options for running Product functions<br><br>Maintenance, which displays options for running Maintenance functions                                                                                                                                                |
|              |      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Tools**    |      | The available options in the Tools menu are:<br><br>Toolbar: When this option is marked, the toolbar is displayed on the CE Utility Workbench window\.<br><br>Function Toolbar: When this option is marked, the function toolbar is displayed on the CE Utility Workbench window\. <br><br>Set User Profile DB Info: This option is used by the Super Administrator user to change the user information that is to be used by the CE Utility for connecting to a database\. <br><br>Window Style: Selecting this option displays a list of CE Utility interface styles: Microsoft Style, Unix Style, Java Style, Classic Style, and Metal Style\. The preferred style may be marked accordingly\. |
|              |      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Help**     |      | The available options in the Help menu are:<br><br>Help Topics: This is *currently not used*\.<br><br>Content Help: This is *currently not used\.*<br><br>About Customer Enterprise: Selecting this option displays the About Customer Enterprise window, which indicates the version information of CE\.                                                                                                                                                                                                                                                                                                                                                                                         |





























Toolbar Buttons

There are two kinds of toolbars in the CE Utility: the basic toolbar and the function toolbar\.





**Basic Toolbar**

The following standard buttons are available on the Basic Toolbar of the CE Utility window\. These are used for performing the basic and common tasks of the system\. 



| ![](./images/4fb68285-f67f-4b9f-ab69-4c03b92c1f10.jpg) |
| :-----------------------------------------------------------: |

***Figure 2\.*** ***4*** ***Basic Toolbar Buttons***





| <span style="color:#000000">**Button**</span> |      | <span style="color:#000000">**Description**</span> |
| :-------------------------------------------: | :--: | :------------------------------------------------: |



| ![](./images/d23b82a7-5847-4bae-a4f9-f2f2589904be.jpg) **New**                       |      | This button is used for creating a new parameter or rule\.                          |
| ------------------------------------------------------------------------------------------: | ---- | ----------------------------------------------------------------------------------- |
|                                                                                             |      |                                                                                     |
| ![](./images/3fb0473b-943e-48c5-a7ec-39fc0c43e614.jpg) **Add**                       |      | This button is used for adding a setting for the selected function or parameter\.   |
|                                                                                             |      |                                                                                     |
| ![](./images/e3320b71-e93e-41ff-8abd-532cd165e9a1.jpg) **Save**                      |      | This button is used for storing created or modified settings\.                      |
|                                                                                             |      |                                                                                     |
| ![](./images/061fc903-4c38-4f8f-af1c-a73ef35d3261.jpg) **Edit**                      |      | This button is used for editing or modifying existing settings\.                    |
|                                                                                             |      |                                                                                     |
| ![](./images/c4f1d95f-b674-41b5-87f6-0df07c8e030f.jpg) **Copy**                      |      | This button is used for copying or duplicating a selected setting\.                 |
|                                                                                             |      |                                                                                     |
| ![](./images/460e029b-fb60-4ff8-aae1-b7c12b70d39e.jpg) **Delete**                    |      | This button is used for deleting or removing an existing setting\.                  |
|                                                                                             |      |                                                                                     |
| ![](./images/1304e0b6-85e3-4242-852c-1cbffce6c4c0.jpg) **Find**                      |      | This button is used for finding an existing setting\.                               |
|                                                                                             |      |                                                                                     |
| ![](./images/41ec4bf3-983b-4f33-a799-31c0f2b6c3db.jpg) **Close Function**            |      | This button is used for closing a function window\.                                 |
|                                                                                             |      |                                                                                     |
| ![](./images/7d438dad-7d46-4e4c-a0a2-761b45c3be14.jpg) **Help Topic**                |      | This button is *currently not used\.*                                               |
|                                                                                             |      |                                                                                     |
| ![](./images/70fa10ec-3a0e-49e1-9b3c-24499fa9a754.jpg) **About Customer Enterprise** |      | This button is used for displaying the version information of Customer Enterprise\. |







**Function Toolbar**

The buttons on this toolbar are shortcuts to some of the functions that are in the Function Group lists of the CE Utility window\. The buttons may also be accessed from the Function menu on the menu bar\.



| ![tmp6387](./images/acc8d42b-7ebc-4ebd-8675-4737e04cece3.jpeg) |
| :-------------------------------------------------------------------: |

***Figure 2\.*** ***5*** ***Function Toolbar Buttons***





| <span style="color:#000000">**Button**</span> |      | <span style="color:#000000">**Description**</span> |
| :-------------------------------------------: | :--: | :------------------------------------------------: |



| ![](./images/144e16ad-73d5-4841-aa1b-ba7371ef95b4.jpg) **Set System Parameter**               |      | This button is used for accessing the System Parameter function\. The function may also be accessed from the Parameter Manage group in the Function menu\.   |
| ---------------------------------------------------------------------------------------------------: | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/6f297b33-69de-4a15-8881-af98c1bccc0d.jpg) **Manage Component**                   |      | This button is used for accessing the Component Manage function\. The function may also be accessed from the Parameter Manage group in the Function menu\.   |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/3b53f14a-46ea-4c21-a02e-7428080e2d47.jpg) **Calculation**                        |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/0f5f9638-9223-4bf0-b010-f5560e787a57.jpg) **Module/Event Configuration**         |      | This button is used for accessing the Module & Event function\. The function may also be accessed from the Transaction Function group in the Function menu\. |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/153d0e19-cecc-4355-aee8-406a2764255d.jpg) **Transaction Function Configuration** |      | This button is used for accessing the Transaction Function\. The function may also be accessed from the Transaction Function group in the Function menu\.    |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/9be8e019-a5bc-4b67-8956-260932e41f3b.jpg) **Form Set**                           |      | This button is used for accessing the Form function\. The function may also be accessed from the Transaction Function group in the Function menu\.           |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/48ea382a-e69d-4f72-bfd1-8d5f29964ebe.jpg) **Accounting Rule Setting**            |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/7293a234-8730-4add-9c14-a22f65e79feb.jpg) **Field Conversion**                   |      | This button is used for accessing the Field Conversion function\. The function may also be accessed from the Maintenance group in the Function menu\.        |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/099129c7-6c1d-465d-8a47-5163c6c2b3b3.jpg)**Get Data**                            |      | This button is used for accessing the Get Data function\. The function may also be accessed from the Transaction Function group in the Function menu\.       |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/8bd8bb19-c495-45c0-b7a5-4b31b716a204.jpg) **Reference Number**                   |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/575d8e7e-0e04-477b-94f6-7551e736daea.jpg) **Output Device**                      |      | This button is used for accessing the Output Device function\. The function may also be accessed from the System Function group in the Function menu\.       |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/c27ed593-58c8-4ca7-b213-b547cab4f692.jpg) **Function Group**                     |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/691269ab-02da-4229-ab81-e158e47154e7.jpg) **Clause**                             |      | This button is used for accessing the Clause function\. The function may also be accessed from the Transaction Function group in the Function menu\.         |
|                                                                                                      |      |                                                                                                                                                              |
| ![](./images/8a5e71ab-9334-4cec-b0ff-12984314926a.jpg) **SWIFT**                              |      | This button is used for accessing the SWIFT Config function\. The function may also be accessed from the Transaction Function group in the Function menu\.   |
|                                                                                                      |      |                                                                                                                                                              |



| ![](./images/8167d336-e584-4147-8383-4cfabc1ed2a3.jpg) **Queue Manager**               |      | This button is used for accessing the Queue Manager function\. The function may also be accessed from the System Function group in the Function menu\.               |
| --------------------------------------------------------------------------------------------: | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/99fc150e-65eb-490d-b0b8-ee03240e3462.jpg) **GAPIs Setting**               |      | This button is used for accessing the GAPIs Setting function\. The function may also be accessed from the Transaction Function group in the Function menu\.          |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/37645f72-29b4-4d3d-848d-b384bc5e4226.jpg) **Time Zone**                   |      | This button is used for setting time zone\. The function may also be accessed from the System Function group in the Function menu\.                                  |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/7bb7a93d-9ade-49a9-b5e2-d66b8575016f.jpg) **STP Setting**                 |      | This button is used for accessing the STP Setting function\. The function may also be accessed from the System Function group in the Function menu\.                 |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/cb537825-baea-4d64-b12e-0ba3a62c8c70.jpg) **Message Broker Setting**      |      | This button is used for accessing the Message Broker Setting function\. The function may also be accessed from the Transaction Function group in the Function menu\. |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/51b4657f-ce4e-4148-b0c5-480e296eb290.jpg) **Processing Center**           |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/ebee1856-62bc-4f5a-a501-65afc2d09a02.jpg) **Amount Format Setting**       |      | This button is used for accessing the Amount/Rate Format function\. The function may also be accessed from the Transaction Function group in the Function menu\.     |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/34cde1a9-250f-4431-81c2-136d8ce339b2.jpg) **Error Message**               |      | This button is used for accessing the Error Message Config \(CE\) function\. The function may also be accessed from the Maintenance group in the Function menu\.     |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/772613d3-2a2b-46e6-bbeb-f37515bf8a8a.jpg) **Say Total**                   |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/df016048-97cf-4b01-ad39-e99136139482.jpg) **Holiday**                     |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/9bd943e0-8f50-46c3-a449-f586285a8734.jpg) **Report**                      |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/b99299e0-12a9-4499-bcf4-ba087119e2d1.jpg) **Transfer To**                 |      | This button is used for accessing the Transfer To function\. The function may also be accessed from the Transaction Function group in the Function menu\.            |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/c4df1ba8-ea47-48a3-a159-cac731284a83.jpg) **Archiving**                   |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/01ac6cee-e390-4b8c-b5e3-0997242dd5a6.jpg) **DB Dictionary**               |      | This button is used for accessing the DB Dictionary function\. The function may also be accessed from the Maintenance group in the Function menu\.                   |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/63e1f5a7-080e-41b0-a196-9de58be4d237.jpg) **Calculation Constant**        |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/6928b0f4-709c-4e5f-9ecc-7b8a46ccd7a7.jpg) **XML Generator**               |      | This button is used for accessing the XML Generator function\. The function may also be accessed from the Maintenance group in the Function menu\.                   |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/b463be57-7e77-46dc-9f01-d795d245e096.jpg) **Business Unit**               |      | This button is used for accessing the Business Unit Config function\. The function may also be accessed from the User Manage group in the Function menu\.            |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/8cf5e1f3-9bf2-4db9-8eaa-675ffcfb4406.jpg) **User Manager**                |      | This button is used for accessing the User Manage function\. The function may also be accessed from the User Manage group in the Function menu\.                     |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/37e5d691-a5d1-4e37-8019-bcaee450ffdb.jpg) **Import/Export Business Unit** |      | This button is used for accessing the Import/Export Business Unit function\. The function may also be accessed from the User Manage group in the Function menu\.     |
|                                                                                               |      |                                                                                                                                                                      |
| ![](./images/23e05679-3f8d-494a-af1a-71afec352f6b.jpg) **DataSource Manager**          |      | This function is used for accessing the Data Source Manage function\. The function may also be accessed from the User Manage group in the Function menu\.            |









Popup Menu

Inside a function or configuration window, options may be provided in the form of a popup menu\. This menu is displayed by right\-clicking on the relevant window section or on the relevant information\. 



| ![](./images/0c4b44da-d696-44ff-bdcc-5e41746ee3a9.jpg) |
| :-----------------------------------------------------------: |

***Figure 2\.*** ***6*** ***Popup Menu***





In a popup window, the following options may be made available:

New

Add

Save

Edit

Copy

Delete

Find

Sharable

Help









Generating the XML Parameter Files

The created parameters and business logic are stored in the database as Meta data\. For this Meta data to be accessible to the application server \(AP\) and the web server, it has to be converted to XML \- the format used for the communication between the client and the server\.

The XML files are generated through the XML Generator function of the Maintenance function group in the CE Utility\. In most cases, the XML Generator function must be run when a parameter is created or modified using the functions discussed in this document\.



| <span style="color:#000000">**Do the following \. \.**</span> <span style="color:#000000">**\.**</span> |
| ------------------------------------------------------------------------------------------------------- |



|  Log on CE Utility as an Administrator or Operator user with rights to the XML Generator function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      | ![](./images/75440bcf-5168-4cef-8d59-c57bb2517a53.jpg) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| The CE Utility window is displayed\.<br><br>Run the XML Generator function from the Maintenance function group\.<br><br>Alternatively, click on the XML Generator button in the function toolbar\.                                                                                                                                                                                                                                                                                                                                                       |      | ![](./images/cf48c7ce-a2e6-4491-9515-5021a603ef14.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| The XML Generator function window is displayed\.<br><br>When there are newly defined or modified parameters, the Meta Data to XML window is also displayed\.  It lists these parameters for easy selection\.  In this case, the parameter can be selected from this window and the Apply button clicked\. Afterwards, proceed to Step 5\.<br><br>Alternatively, the Meta data or parameter can be manually selected from the main XML Generator window\.  In this case, click on the Close button of the Meta Data to XML window and proceed to Step 4\. |      | ![](./images/47110a98-c775-459e-a29e-e23f41cfd1a1.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| Double\-click on the relevant parameter type from the XML Generator window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](./images/913097b5-61c6-4bec-b6f6-68988b1c95f6.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| Depending on the selected parameter type, an XML configuration window may be displayed\. In other cases, the process directly proceeds to Step 6\.<br><br>If the configuration window is displayed, indicate the exact or any additional setting required to generate the relevant XML files\. When the specifications are defined click on the Save button                                                                                                                                                                                              |      | ![](./images/846f96a8-242d-41f6-9f71-749e887386e4.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| A message is displayed confirming if the XML files are to be generated on the system path\.                                                                                                                                                                                                                                                                                                                                                                                                                                                              |      | ![](./images/508b7416-f9b3-4ff3-9664-5199d4a2178c.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">The path of the XML files is defined through the GEN\_XML\_ROOTPATH Utility Workbench system parameter\. This system parameter is configured through the System Parameter function from the Parameter Manage function group\.</span>                                                                                                                                                                                           |      | ![](./images/e61ff9f5-e075-4ea8-8dfb-97d3ada29d6a.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| To save the XML file on the relevant system path, click on the Yes button\.<br><br>To specify another path, click on the No button\. On the Save dialog box that is displayed, browse for the path and click on the Save button\.                                                                                                                                                                                                                                                                                                                        |      | ![](./images/6205941d-407c-462d-8274-cd8b757e9312.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| When the relevant XML files are generated, the system displays a confirmation message\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">To hide the information on the paths of the generated XML files, click on the Hide button\.</span>                                                                                                                                                                                                                      |      | ![](./images/0949cae8-f687-4402-8a89-5bd5590a3b36.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">Check the indicated path\(s\) to see the generated XML files\.</span>                                                                                                                                                                                                                                                                                                                                                          |      | ![](./images/98850beb-3e71-4194-8370-b613d4e6219c.jpg) |











Building a Product

When building a product in the CE Utility, a few prerequisites are required to be met to make sure that modules or products are built in accordance with the bank's requirements\.  One step is the GAP analysis which involves an evaluation of transaction requirements, based on the process flow \(e\.g\., fields, clauses, forms, and interfaces\)\.  These are necessary for identifying the fields required for anticipating the required output\.  When the analysis has been completed, the project team can now begin the process of building a product for the bank's customers\.

The following are steps in building a product:



**Access the CE Utility**\.  To access the CE Utility for building parameters, an Operator user must be created by an Administrator user\.  This is set up through the User Manager function in the User Manage function group\.

**Set up the module and events**\.  This involves naming the module and the projected events that manage the transaction flow within the module\.  This is set up in the Module and Event function in CE Utility\.

**Set up the transaction tables\.** This involves creating the tables in the DB Dictionary function in CE Utility\.  There can be different types of tables but only three are mandatory for a CE module: master, ledger, and event\. 



![Tzone55](./images/ec3dfc40-081a-4fac-a0c1-92a49ac7ef10.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**It is possible to create tables directly into the database by running SQL scripts in the database\.  In this case, tables can be created before modules and events\.  It is recommended, however, to use the DB Dictionary for creating tables\.**</span>





**Add fields to the transaction table**\.  Fields must be added to a transaction table and field properties defined for the processing and storage of data\.  These can be done through the DB Dictionary function in CE Utility\.

**Set up the transaction functions**\.  This involves creating the functions that correspond to actual business transaction processes\.  This is done through Transaction Function in the Transaction Function group\.

**Set up the transaction parameters**\.  This involves designing the transaction screen, defining attribute and catalog settings, and attaching these parameters to the transaction function\.  These can be done through Transaction Function in CE Utility\.

**Create the product\.** The product is the actual functionality accessed and run by the end\-user\.  This process of creating a product involves setting up the product group, product, and product function, and defining product catalog settings\.

**Define authorization rules**\.  Authorization rules are set to further define or set limits for authorizing transactions\. 

**Calculation\.** This involves configuring the transaction JS files and defining calculation functions using available system methods\.  There are three JS files that have to be configured: the Module Base JS file, Event JS file, and Function JS file\.

**Define the settings for the transaction input\.** Certain functions may be added to aid in the input of data into the transaction\.  The CE Utility provides options for setting up field conversion rules, lookup buttons, customer reference numbers, clauses, dropdown lists, and data objects for this purpose\.

**Define the settings for the transaction output\.** Some business transactions involve output generation \(i\.e\., Forms\)\.  To make this option available, certain settings must be configured using the functions from the Transaction Function group in CE Utility\. 

**Define the security settings in the CE browser\.** The products and functions created are assigned to an end\-user through the browser\-side Security and System Maintenance functions\.



![Tzone55](./images/986153cd-e1b2-48a0-acef-c85155fa96dd.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**The browser\-side security and system maintenance functions of CE are often collectively called the Security Module\.**</span>





**Add the Inbox functionality\.** Another way of accessing a product or a transaction for further processing is through the Customer Inbox\.  This can be set up through the Inbox function in CE Utility\.



![Tzone55](./images/d9bf9932-77d4-49a6-a98d-3dee92068594.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**For more information on configuring different parameters in CE, refer to the**</span> <span style="color:#008080">***CE Utility Reference***</span> <span style="color:#008080">**manuals**</span><span style="color:#008080">***\.***</span>









Archiving Prerequisites

Archiving / BACKUP Database Settings

Data Source Settings

Log Settings

Archiving / Backup Database Settings

Transaction records are archived into a separate Backup Database, i\.e\., the archiving database\.  

This Backup Database must have the same table structure as the physical Transaction Database\.  When the table structures of the Transaction Database is changed, modify the corresponding table structures in the Backup Database by manually running the relevant SQL statements in this archiving database\.





![Tzone55](./images/2d475b1f-5281-430d-a42e-d13a057a340c.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">The Backup</span> <span style="color:#008080">Database</span> <span style="color:#008080">setting</span><span style="color:#008080">s</span> <span style="color:#008080">must be configured in the same application server \(WAS\)\.</span>





Data Source Settings

For the Archiving and Recovery functionality of the CE system, two data sources are required: CEB and CEX\.

The CEB data source refers to the Backup data source and, thus, points to the physical archiving database\. Used for storing archived data, this Backup Database has the same table structure as the Transaction Database\.

The CEX data source points to the physical Transaction Database, and is essentially the same as the CET data source\.

The settings for the CEB and CEX data sources are configured in both WebSphere and CE Utility\.







WebSphere Data Source Settings

The required WebSphere settings are as follows\.



| <span style="color:#BFBFBF">**Do the following \. \. \.**</span> |
| ---------------------------------------------------------------- |



| Define the JDBC provider:<br><br>Name: Oracle JDBC Driver \(XA\)<br><br>Implementation class name: oracle\.jdbc\.xa\.client\.OracleXADataSource<br><br>Class path: $\{ORACLE\_JDBC\_DRIVER\_PATH\}/ojdbc6\.jar<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">ojdbc6\.jar</span> <span style="color:#008080">file is the JDBC driver for Oracle</span> <span style="color:#008080">12c</span><span style="color:#008080">\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      | ![](./images/b78e455b-637c-4b61-b11d-7c5ea1b780ad.jpg)                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | :--------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                                    |
| Define the CEB data source:<br><br>Name: CEB<br><br>JNDI Name: CEB                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](./images/bcdc4361-9499-48ff-ac20-84ec480af530.jpg)                                                                      |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                                    |
| This must point to the Backup Database \(e\.g\., CEBK\)\.<br><br>Assign CETRX for:<br><br>Authentication alias for XA recovery<br><br>Component\-managed authentication alias<br><br>Container\-managed authentication alias<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">CETRX user</span> <span style="color:#008080">created</span> <span style="color:#008080">in the Oracle Database is</span> <span style="color:#008080">the user that is to access the Backup D</span><span style="color:#008080">atabase\. If this is not the same as the transaction database user, the</span> <span style="color:#008080">CETRX</span> <span style="color:#008080">alias</span> <span style="color:#008080">must</span> <span style="color:#008080">be set in the Global Security tab, JAAS \- J2C Authentication Data page of the WebSphere Application Server Administrative Console\.</span>  |      | ![](./images/36904b91-2328-4e84-9593-89c8347808c2.jpg)<br><br>![](./images/17f307fc-439c-400a-b80b-6f2de3e1f0a4.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                                    |
| Define the CEX data source:<br><br>Name: CEX<br><br>JNDI Name: CEX                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](./images/b9065b83-d8f1-4537-b705-615f0ee5650b.jpg)                                                                      |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                                    |
| This must point to the Transaction Database \(e\.g\., CEDB\)\.<br><br>Assign CETRX for:<br><br>Authentication alias for XA recovery<br><br>Component\-managed authentication alias<br><br>Container\-managed authentication alias<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The CETRX user is the same as the</span> <span style="color:#008080">CETRX user that is used to access the transaction database</span><span style="color:#008080">\.</span><br><br><span style="color:#008080">The CEX data source points to the physical Transaction Database, and is essentially the same as the CET data source\.</span>                                                                                                                                                                                                                                                                                                         |      | ![](./images/2edd12bb-c48f-4ff9-9997-1474736a2b7d.jpg)<br><br>![](./images/d24b7c46-8e1a-4e7b-9fcf-7b33e5265d5f.jpg) |





CE Utility Data Source Settings

Log on the CE Utility as a Super Administrator user and configure the following data source settings\.



| <span style="color:#BFBFBF">**Do the following \. \. \.**</span> |
| ---------------------------------------------------------------- |



| Run the DataSource Manage function from the User Manage group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](./images/cc10bd1c-d5d4-4924-98f0-027e62d150e6.jpg) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | ------------------------------------------------------------- |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| Check the settings in the Transaction Data Source Manager tab of the DataSource Manage function window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![](./images/a0d02fbe-1f0e-45ac-971e-b2a3f67c6796.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| Modify or create the CEX data source\.<br><br>This data source must point to the Transaction Database, and reference the CEX JNDI setting and CETRX user profile\.<br><br>Make sure to select Archiving as the database type\.                                                                                                                                                                                                                                                                                                                                                                           |      | ![](./images/e68b4d21-8868-41b2-a7c2-a2681a28b773.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| Modify or create the CEB data source\.<br><br>This data source must point to the Backup Database, and reference the CEB JNDI setting and CETRX user profile\. <br><br>Make sure to select Backup as the database type\.<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">CETRX is the CE Transaction Database user that is to access the Backup Database\.</span>                                                                                                                                                                                   |      | ![](./images/ee8fd905-c4e4-47cc-9d56-a9e398ec21b8.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| <u><span style="color:#008080">**XML GENERATION:**</span></u><br><br><span style="color:#008080">Log on as an Administrator or Operator user and run the XML Generator function\.</span><br><br><span style="color:#008080">Generate the XML file for the Data Source Manage</span><span style="color:#008080">r</span> <span style="color:#008080">parameter\.</span>                                                                                                                                                                                                                                   |      | ![](./images/63766067-e007-49a0-9e64-8e8ecc5b1143.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                               |
| <span style="color:#008080">The updated XML files are generated</span> <span style="color:#008080">on</span> <span style="color:#008080">this path:</span><br><br><span style="color:#008080">\[Parameter Drive\]\</span><span style="color:#008080">C</span><span style="color:#008080">E\_SYS\SYST</span><br><br><span style="color:#008080">The updated</span> <span style="color:#008080">ee\_dsmgr\.xml</span> <span style="color:#008080">file contains</span> <span style="color:#008080">details</span> <span style="color:#008080">on the bank groups which data sources have been set\.</span> |      | ![](./images/a4d27001-9ea5-48a5-a38f-f51687cf5a1b.jpg) |



Log Settings

Configure the settings for the Archive logs through this file:

\[CE Parameter Folder\]\CE\_SYS\CE\_Log\_Config\.xml



<u><span style="color:#008080">**EXAMPLE:**</span></u>

<span style="color:#008080">Archive Log</span> <span style="color:#008080">configuration</span> <span style="color:#008080">settings:</span>



![tmp114.jpg](./images/d3e323e2-4fda-4f44-bb77-235f01b65b80.jpeg)





For detailed information on log configuration, refer to the *CE Log Settings* documentation\.





Manual Archive Mode

Overview

COMMON pARAMETER Settings

ARCHIVE DATA FUNCTION

Restore Archived Data Function

Inquire Archived Data function



Overview

With the Manual Archive mode, the archiving process is performed by module\. The archiving functions are grouped and accessed under a particular transaction module\. Moreover, only the records that satisfy the defined set of criteria can be accessed and processed under an Archive function\.

The Manual Archive functions that may be created under a business transaction module are as follows:

Archiving Data

Inquire Archived Data

Restore Archived Data





Common Parameter Settings

Configuring manual Archiving functions involves common prerequisite parameters\.





Archive Control Component

Trx Manager Archive, a Control component, is used for 2 manual Archiving functions: Archive Data and Restore Archived Data\.

Log on the CE Utility as an Operator user and define the following settings\.



| Do the following \. \. \. |
| :------------------------ |



| Run the Component Manage function from the Parameter Manage function group\.                                                                                                                                                      |      | ![](./images/f4433d21-7e07-4c5e-a9fd-a84765001b96.jpg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                   |      |                                                               |
| Access the Control component type\.                                                                                                                                                                                               |      | ![](./images/cb508f37-9ad4-4155-b9b3-b843f9b9f8aa.jpg) |
|                                                                                                                                                                                                                                   |      |                                                               |
| Check or add the Trx Manager Archive Control component:<br><br>Component Name: Trx Manager Archive<br><br>Component Description: Trx Manager Archive<br><br>Class Name: TrxManagerArchive<br><br>Business Type: Delete Master Mgr |      | ![](./images/537217d7-9a65-4f64-9f56-07d863977914.jpg) |





Archive Product Items

Specific Archive product items are required to associate a manual Archiving function to the relevant Archiving product\.

Add the following product items \- 

Archive

RestoreArchive

InquireArchive



\- to this file:

\[CE Utility Directory\]\ce\_params\Script\_XML\product\_item\_prar\.xml\.



| ![](./images/0308dd1a-c1bc-40d3-944c-d41631262a67.jpg) |
| ------------------------------------------------------------- |

Figure 4\.  Product Items for Archiving







Once these product Ids are defined in the XML file, add these in the Product Item function\.  Log on the CE Utility as an Operator user:



| Do the following \. \. \. |
| :------------------------ |



| Run the Product Item function from the Product Function group\.                                                                                                                                                                                               |      | ![](./images/7973a0d5-4410-4850-bff8-0f432dddd9b5.jpg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                               |      |                                                               |
| Add the Archive item Id:<br><br>Item ID: Archive<br><br>Item Name: Archive<br><br>Item Desc: Archive<br><br>Is Group: No<br><br>Position: Transaction<br><br>Item Button: Archive<br><br>Type: Delete                                                         |      | ![](./images/e72acbc5-19b8-4760-8a5d-a88ae23622db.jpg) |
|                                                                                                                                                                                                                                                               |      |                                                               |
| Add the RestoreArchive item Id:<br><br>   Item ID: RestoreArchive<br><br>   Item Name: RestoreArchive<br><br>   Item Desc: RestoreArchive<br><br>   Is Group: No<br><br>   Position: Transaction<br><br>   Item Button: RestoreArchive<br><br>   Type: Delete |      | ![](./images/994d75de-4551-4397-b947-de362b159d9e.jpg) |
|                                                                                                                                                                                                                                                               |      |                                                               |
| Add the InquireArchive item Id:<br><br>Item ID: InquireArchive<br><br>Item Name: InquireArchive<br><br>Item Desc: InquireArchive<br><br>Is Group: No<br><br>Position: Transaction<br><br>Item Button: InquireArchive<br><br>Type: Inquire                     |      | ![](./images/e241fd3c-4461-4607-82e7-d933cfb6b878.jpg) |



Error Codes

Log on the CE Utility as an Operator user and define the following error codes for Archiving processes\.



| Do the following \. \. \. |
| :------------------------ |



| Run the Error Handling function from the Maintenance function group\.                                                                                                      |      | ![](./images/03d687a1-3a62-4106-8c82-a68d90f824bb.jpg) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                            |      |                                                               |
| In the Catalog tab of the Error Handling function window, access the System node\.                                                                                         |      | ![](./images/5ecbcfbd-899d-4ad5-8a7d-cb758c7cdab7.jpg) |
|                                                                                                                                                                            |      |                                                               |
| Check or add Error Code 000464:<br><br>Error Code: 000464<br><br>Error Key: System<br><br>Error Level: Error<br><br>Error Messge: "Archive failure"                        |      | ![](./images/a743b962-034e-4a34-bf32-32e74a943136.jpg) |
|                                                                                                                                                                            |      |                                                               |
| Check or add Error Code 000465:<br><br>Error Code: 000465<br><br>Error Key: System<br><br>Error Level: Error<br><br>Error Messge: "Exception occur when restoring Archive" |      | ![](./images/76eb23c4-7b04-4bd2-93b6-ba59a46b41c4.jpg) |





JSP and JS Settings

Modify the JSP and JS settings of the relevant transaction module to support the Archiving and Recovery functionality\.

Examples of such settings are provided in [Appendix:](<error reading>) \.



Archive Data Function

This function is used for archiving records\.  



![Tzone55](./images/a60c46df-3561-452f-85f3-231a8e2edd58.jpeg)<span style="color:#008080">NOTE:</span> 

<span style="color:#008080">**Archived records are stored in the Backup Database\.  An archived transaction can be restored through the Restore Archived Data function\.**</span>

<span style="color:#008080">**Multiple records can be archived at a time**</span> <span style="color:#008080">**by adding**</span> <span style="color:#008080">**the**</span> <span style="color:#008080">**following**</span> <span style="color:#008080">**code**</span> <span style="color:#008080">**in the**</span> <span style="color:#008080">**multiCheck**</span> <span style="color:#008080">**function**</span> <span style="color:#008080">**found**</span> <span style="color:#008080">**in the**</span> <span style="color:#008080">**SYS\_MultiCatalog\.js**</span> <span style="color:#008080">**file:**</span>   <span style="color:#008080">**:: ITEM\_ID == "Archive" :: ITEM\_ID == "RestoreArchive"\)**</span>



<span style="color:#008080">**Example**</span><span style="color:#008080">**:**</span>

<span style="color:#008080">**function multiCheck\(\)\{**</span>

 <span style="color:#008080">**try \{**</span>

    <span style="color:#008080">**if \(ITEM\_ID == "Authorize" :: ITEM\_ID == "Authorise"**</span> <span style="color:#008080">::</span> <span style="color:#008080">**ITEM\_ID == "Archive" :: ITEM\_ID == "RestoreArchive"\)**</span> <span style="color:#008080">**\{**</span>

    <span style="color:#008080">**return true;**</span>

 <span style="color:#008080">**\}**</span>

 <span style="color:#008080">**\}**</span> 

 <span style="color:#008080">**catch \(e\) \{**</span>

 <span style="color:#008080">**showExcpt\("SYS\_MultiCatalog", e\);**</span>

 <span style="color:#008080">**\}**</span>

<span style="color:#008080">**\}**</span>







Parameter Settings

Log on CE Utility as an Operator user and configure the following transaction function and product settings\.





Transaction Function Settings



| Do the following \. \. \. |
| :------------------------ |



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![](./images/59c0e358-f640-45b3-9c15-151eadcaedac.jpg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                               |
| Access the module and function group for which the Archive Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                            |      | ![](./images/55649846-0870-4b0f-9ea4-0f89bb7cf826.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                               |
| Create the Archive Data function and set its main program to Trx Manager Archive\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Archive Data</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Unmark the following flags:</span><br><br><span style="color:#008080">Check for Lock in Master</span><br><br><span style="color:#008080">Hold Master</span><br><br><span style="color:#008080">Need Lock</span><br><br><span style="color:#008080">Release</span> |      | ![](./images/62f2a475-9b81-4f7b-adf9-8cc45984a35e.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                               |
| Define the relevant Attribute settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](./images/94fbba8d-c324-47eb-b9e6-272d64f66b86.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                               |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      | ![](./images/06f2ffd6-f3b8-4176-980e-a487ab1e3e68.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                               |
| <u><span style="color:#008080">**NOTE**</span></u><u><span style="color:#008080">**:**</span></u><br><br><span style="color:#008080">If this manual Archive function is to be used to archive a record that has been received via STP, the STP settings must also be configured through the STP function component\.</span><br><br><span style="color:#008080">For</span> <span style="color:#008080">details</span> <span style="color:#008080">on STP Archive functions, refer to:</span><br><br>Chapter Six: Archiving through STP                                                                  |      | ![](./images/12f86dc1-af71-4c79-b305-e9d377d86dde.jpg) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](./images/44e8eb56-35f7-49f8-a390-ad50128a32c1.jpg) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](./images/3d236268-8e61-4e1d-9eea-aa540458b379.jpg) |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Select the Archive Data function \(e\.g\., IMLC Archive Data\) and assign these settings:<br><br>Item: Archive<br><br>Item Type: Delete                                                                                                                                                         |      | ![](./images/d7a4e3ab-ed9a-49b1-aa67-6581f449c18a.jpg) |



Transaction Process



| EXAMPLE |
| :------ |



| IMLC Archive Data Function<br><br>Run the IMLC Archive Data function\.                                                                                                                                                                                                            |      | ![tmp118.jpg](./images/d894e7d6-c235-4d6f-8134-515573a5e6ef.jpeg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :----------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| Select one record and click on the Archive button\.<br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp119.jpg](./images/d8e42850-c9c3-4518-a2e1-3d125f7bbe0c.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| IMLC Inquire Archive Function<br><br>Run the IMLC Inquire Archive function\. <br><br>The catalog shows the archived record\.  Select this record and click on the InquireArchive button\.                                                                                         |      | ![tmp120.jpg](./images/4d175236-5855-4920-9a0f-1a39cbc2e60b.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| The documents and uploaded images for this record are listed for viewing \(through the corresponding View buttons\)\.                                                                                                                                                             |      | ![tmp121.jpg](./images/c805ee95-5076-4e53-ae01-56043761bb17.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| Click on the View Historical button\.                                                                                                                                                                                                                                             |      | ![tmp122.jpg](./images/32b2b48a-bb6d-45b1-9dad-06e526b529de.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| The events of the transaction record are listed\.                                                                                                                                                                                                                                 |      | ![tmp123.jpg](./images/5709e09b-d6f7-4055-98b1-322d14b16985.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                          |
| Select an event to view the event details\.                                                                                                                                                                                                                                       |      | ![tmp124.jpg](./images/5781fe6e-ccd5-4ca0-bad9-091a9ae7c07e.jpeg) |





Restore Archived Data Function

This function is used to retrieve transactions from the Backup Database, and add these back to the master file\.

When the record to be restored already exists in the Transaction Database, the Restore process may not be performed on this record\.

When a record is restored, all related events are also restored in the corresponding tables\.





![Tzone55](./images/2a8d7a8e-e86a-400c-853e-686049c7333f.jpeg)<span style="color:#008080">NOTE:</span> 

<span style="color:#008080">**M**</span><span style="color:#008080">**ultiple records**</span> <span style="color:#008080">**may be restored by adding the following code in the**</span> <span style="color:#008080">**multiCheck**</span> <span style="color:#008080">**function**</span> <span style="color:#008080">**found**</span> <span style="color:#008080">**in the**</span> <span style="color:#008080">**SYS\_MultiCatalog\.js**</span> <span style="color:#008080">**file:**</span>  <span style="color:#008080">**:: ITEM\_ID == "Archive" :: ITEM\_ID == "RestoreArchive"\)**</span>



<u><span style="color:#008080">EXAMPLE:</span></u>

<span style="color:#008080">**function multiCheck\(\)\{**</span>

 <span style="color:#008080">**try \{**</span>

    <span style="color:#008080">**if \(ITEM\_ID == "Authorize" :: ITEM\_ID == "Authorise"**</span> <span style="color:#008080">::</span> <span style="color:#008080">**ITEM\_ID == "Archive" :: ITEM\_ID == "RestoreArchive"\)**</span> <span style="color:#008080">**\{**</span>

    <span style="color:#008080">**return true;**</span>

 <span style="color:#008080">**\}**</span>

 <span style="color:#008080">**\}**</span> 

 <span style="color:#008080">**catch \(e\) \{**</span>

 <span style="color:#008080">**showExcpt\("SYS\_MultiCatalog", e\);**</span>

 <span style="color:#008080">**\}**</span>

<span style="color:#008080">**\}**</span>

<span style="color:#008080">**The system restores multiple r**</span><span style="color:#008080">**ecords one at a time\.**</span> <span style="color:#008080">**After restoring the first selected record**</span><span style="color:#008080">**, the system provides a Continue button to**</span> <span style="color:#008080">**enable the user to**</span> <span style="color:#008080">**restore the next selected records\.**</span>  













Parameter Settings

Log on CE Utility as an Operator user and configure the following transaction function and product settings\.





Transaction Function Settings



| Do the following \. \. \. |
| :------------------------ |



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![](./images/53b8d0a4-5b65-4761-9736-8f72b3359d61.jpg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Access the module and function group for which the Restore Archived Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                               |      | ![](./images/2018d3b1-8f78-4d76-97bc-93cd68b6edd3.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Create the Restore Archived Data function and set its main program to Trx Manager Archive\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Restore Archive</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Unmark the following flags:</span><br><br><span style="color:#008080">Check for Lock in Master</span><br><br><span style="color:#008080">Hold Master</span><br><br><span style="color:#008080">Need Lock</span><br><br><span style="color:#008080">Release</span> |      | ![](./images/04c95b59-efca-4cd6-9837-975aa4067442.jpg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![](./images/cedf0d9b-56b7-4c82-a637-4babd7a0d8d9.jpg) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](./images/820cc69a-2da7-4b35-87ee-1e06d514a756.jpg) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](./images/7d341cac-c124-4606-9860-5b4a458e08b9.jpg) |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Select the Restore Archived Data function \(e\.g\., IMLC Restore Archive\) and assign these settings:<br><br>Item: RestoreArchive<br><br>Item Type: Delete                                                                                                                                      |      | ![](./images/bb10e75f-3ae7-4247-9f1a-d98a04aea70c.jpg) |



Transaction Process






-----

<span style="color:red">**Table has a different set of cells in one/more rows. It can't be shown in Markdown**</span>

-----






Inquire Archived Data Function

The Inquire Archived Data function is used to inquire into records that are stored in the Archive file\.





![Tzone55](./images/99b3dd0a-b31e-4bd2-b677-64efeed7af54.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**Unlike other**</span> <span style="color:#008080">**inquiry**</span> <span style="color:#008080">**functions, the Inquire Archived Data function retrieves**</span> <span style="color:#008080">**details**</span> <span style="color:#008080">**from the Backup Database \(i\.e\., CEB data source\) and not from the Transaction Database\.**</span>







Parameter Settings

Log on CE Utility as an Operator user and configure the following transaction function and product settings\.





Transaction Function Settings



| Do the following \. \. \. |
| :------------------------ |



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                     |      | ![](./images/68a659c4-6fab-48ca-878c-4ef42a5ed315.jpg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Access the module and function group for which the Archive Data is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span> |      | ![](./images/bd412661-0985-49ce-b820-1bd34db70bd6.jpg) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Create the Inquire Archived Data function and set its main program to Trx Manager Inq\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Inquire Archive</span>                                                                             |      | ![](./images/052855dd-7533-4e54-b4f6-ddbaa0ec635a.jpg) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Attach the transaction JSP and template JSP files to this function\.                                                                                                                                                                                                                                               |      | ![](./images/6b8bf30f-1abc-43f1-b347-e32f298b4d91.jpg) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Define the relevant Attribute settings for this function\.                                                                                                                                                                                                                                                         |      | ![](./images/43540f45-68cf-4b4c-948b-602166f3f16d.jpg) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                               |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                           |      | ![](./images/b0ab1104-0a51-4df0-b2ea-e66b630710c4.jpg) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](./images/62930ba6-c7a9-4937-8c5b-cb3374483342.jpg) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-----------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](./images/21d1a31d-477b-412c-acf7-265832878191.jpg) |
|                                                                                                                                                                                                                                                                                                 |      |                                                               |
| Select the Inquire Archived Data function \(e\.g\., IMLC Inquire Archive\) and assign these settings:<br><br>Item: InquireArchive<br><br>Item Type: Inquire                                                                                                                                     |      | ![](./images/46b6b827-298d-49cf-a6ca-29cbf61e4b84.jpg) |



Transaction Process



| EXAMPLE |
| :------ |



| Through the IMLC Archive Data function, archive one record\.                                                                                         |      | ![tmp119.jpg](./images/81419ae1-c251-4209-a3bd-f988a1a349a1.jpeg) |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :----------------------------------------------------------------------: |
|                                                                                                                                                      |      |                                                                          |
| Run the IMLC Inquire Archive function\. <br><br>The catalog shows the archived record\.  Select this record and click on the InquireArchive button\. |      | ![tmp120.jpg](./images/45172aa0-4416-4eb7-bba9-927c76adeb38.jpeg) |
|                                                                                                                                                      |      |                                                                          |
| The documents and uploaded images for this record are listed for viewing \(through the corresponding View buttons\)\.                                |      | ![tmp121.jpg](./images/efef0bdd-d4c1-4ac8-81ed-842a86d8604a.jpeg) |
|                                                                                                                                                      |      |                                                                          |
| Click on the View Historical button\.                                                                                                                |      | ![tmp122.jpg](./images/2993baab-8b49-4aa0-a7a6-2ba93c0dcdfd.jpeg) |
|                                                                                                                                                      |      |                                                                          |
| The events of the transaction record are listed\.                                                                                                    |      | ![tmp123.jpg](./images/3f53ab28-1090-4a2d-84da-543f000eb154.jpeg) |
|                                                                                                                                                      |      |                                                                          |
| Select an event to view the event details\.                                                                                                          |      | ![tmp124.jpg](./images/e76b6064-d996-45c3-b29d-26b4dd48090c.jpeg) |





Auto Archive Mode

Overview

parameter SEttings

Transaction Process



Overview

With the Auto Archive mode \(or batch mode\), records from the relevant module that satisfy a defined set of criteria for the module are automatically archived\.  

The AutoArchiveData batch function is an example of an Auto Archive function\.





![Tzone55](./images/743aab06-ea87-4722-84de-72cec4930960.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**Each module has its own Archive conditions, which are set through the**</span> <span style="color:#008080">**Sub Task function**</span> <span style="color:#008080">**of the CE Utility\.**</span>  <span style="color:#008080">**Refer to the**</span> <span style="color:#008080">**succeeding**</span> **[Par](<error reading>)** <span style="color:#008080">**section for more**</span> <span style="color:#008080">**details**</span> <span style="color:#008080">**on setting the archive conditions for each module\.**</span>





 





Parameter Settings

One of the tasks under the AutoProcessTaskMgr batch manager, the AutoArchiveData batch function is used to automatically archive transaction records from a particular module that satisfy a defined set of criteria\.

The parameter settings for this batch function involve settings in the Sub Tasks, AP Server, Import/Export Business Unit, and Batch Manage functions\.  Log on the CE Utility as an Operator user and configure the following settings\.



| Do the following \. \. \. |
| :------------------------ |



| Sub Tasks<br><br>Run the Sub Tasks function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![CEv3_189.jpg](./images/de1922ed-0fb8-4541-9f48-6d8b780dd896.jpeg)     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :----------------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Access the Auto Process Manage subtask type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![CEv3_190.jpg](./images/e025b57f-9198-42a9-bbac-c79918c5a962.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Configure the AutoArchiveData settings as required, and make sure to define the following:<br><br>Task Name, Task Description, Task Component: AutoArchiveData<br><br>Start Schedule Type and related settings<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">Month, Week Day, Day,</span> <span style="color:#008080">and</span> <span style="color:#008080">Hour</span> <span style="color:#008080">fields are enabled based the Start Schedule Type field setting\. Define the values of these fields as well as the Minute component of the archive task schedule accordingly\. Refer to the</span> <span style="color:#008080">*CE Utility Referenc*</span><span style="color:#008080">*e*</span><span style="color:#008080">*:*</span> <span style="color:#008080">*Transaction Functions*</span> <span style="color:#008080">documentation</span> <span style="color:#008080">for more</span> <span style="color:#008080">details</span> <span style="color:#008080">on these settings\.</span><br><br><span style="color:#008080">Marking the Start Server flag allows a user to manually start the AutoArchiveData task\.</span><br><br><span style="color:#008080">The Time</span><span style="color:#008080">r</span> <span style="color:#008080">\(Hours\) field pertains to the duration within which the system archives the records that meet the criteria\.  If the records are not archived completely within this period, the system terminates the archive process\.</span>  |      | ![CEv3_191.jpg](./images/c775df63-a239-4d69-9dee-f733b4bfc239.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| AP Server<br><br>Run the AP Server function from the Parameter Manage function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      | ![CEV30_Archive-02](./images/23815255-3138-4e14-977c-235987deb184.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Define or modify the AP Server settings: Name, Host Name, and IIOP Port\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEV30_Archive-03](./images/db409a40-3708-4f87-88b2-0c0acf40b98b.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Import/Export Business Unit<br><br>Run the Import/Export Business Unit function from the User Manager function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      | ![CEV30_Archive-04](./images/07589a9b-6a22-410d-9dbf-ec9f87cc5414.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| In the Import/Export Business Unit window, select the Application Server setting and click on the Import button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![CEV30_Archive-06](./images/ef0b20c7-6456-4fb2-9609-a349b5a046d0.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Batch Manage<br><br>Run the Batch Manage function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_192.jpg](./images/fcb45cdf-3c65-49ed-850a-1a086ff98c2d.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Create or modify the AutoProcessTaskMgr batch manager\. Select the correct AP Server Name setting\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![CEV30_Archive-08](./images/3f065ed7-d495-4d6c-84ea-68901058a4c4.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Add AutoArchiveData as a subtask of the AutoProcessTaskMgr batch manager\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      | ![CEv3_193.jpg](./images/dfac953e-b99c-4d5d-9d91-02b0199b5583.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Sub Tasks<br><br>Run the Sub Tasks function from the Transaction Function group\.<br><br>Access the Archiving subtask type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |      | ![CEv3_194.jpg](./images/53ba29ff-7038-4b1f-955f-d24dfbc60027.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |
| Access the relevant module and define the following settings\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_196.jpg](./images/a7913558-38bd-4796-a48e-e102f9246934.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                                |



| Fields: Select PARENT\_MAIN\_REF <br><br>This reference number is used to identify the transaction and all its associated data \(e\.g\., images, documents\)\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_197.jpg](./images/a8f604d7-64e0-42f7-99ee-52c117374333.jpeg)     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :----------------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                                |
| In the text area, define the condition by which records from the module are archived\.<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The SQL keywords \- such as</span> <span style="color:#008080">SELECT</span> <span style="color:#008080">and</span> <span style="color:#008080">FROM</span> <span style="color:#008080">\- must be in uppercase\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |      | ![CEv3_198.jpg](./images/fb028687-b18b-4014-af37-0b932f2d338b.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                                |
| <u><span style="color:#008080">**XML GENERATION:**</span></u><br><br><span style="color:#008080">Generate the XML file for the</span> <span style="color:#008080">Archive</span> <span style="color:#008080">parameter\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![CEv3_199.jpg](./images/29f25af3-1414-4b21-8595-e75695c90d74.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                                |
| <span style="color:#008080">Select</span> <span style="color:#008080">all</span> <span style="color:#008080">module</span><span style="color:#008080">s</span><span style="color:#008080">\.</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Selecting a</span><span style="color:#008080">ll modules</span> <span style="color:#008080">is recommended as the system</span> <span style="color:#008080">generates XML only for the selected modules and</span> <span style="color:#008080">deletes all previously generated XML for</span> <span style="color:#008080">the unselected</span> <span style="color:#008080">modules from the Archive folder</span> <span style="color:#008080">under the</span> <span style="color:#008080">CE\_SYS</span> <span style="color:#008080">directory</span><span style="color:#008080">\.</span> |      | ![CEV30_Archive-10](./images/4a837534-44b7-461f-a6ca-de1c88eb8dfd.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                                |
| <span style="color:#008080">The following files are generated in</span> <span style="color:#008080">\[Parameter Drive\]\CE\_SYS\ARCHIVE:</span><br><br><span style="color:#008080">autoporcess\.xml</span><br><br><span style="color:#008080">module\_\[module short name\]\.xml</span><br><br><span style="color:#008080">multiPending\.xml</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEV30_Archive-11](./images/48bc9dda-6d87-4cec-b353-0f48d2f8db23.jpeg) |









Transaction Process



| EXAMPLE: |
| :------- |



| Run the Batch Manager function and display the AutoProcessTaskMgr task manager\.<br><br>Start the AutoArchiveData subtask\.                                                                                                                                                                                                                                                                                                                               |      | ![tmp126.jpg](./images/6edfa000-19f7-4b2b-89a4-b9b27d9c242e.jpeg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :----------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                          |
| Execute this SQL to check which records meet the archiving filter condition\.                                                                                                                                                                                                                                                                                                                                                                             |      | ![tmp127.jpg](./images/2c42cb16-b7ea-4459-8e85-6becfa5b5f58.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                          |
| Three records are archived according to the archiving period and archiving condition specified in the parameters\.  \(These pertain to the Auto Process Manage and Archiving settings defined in the Sub Tasks function\.\)<br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp128.jpg](./images/cdcd4115-b70c-4c45-b31b-d443a7c8878c.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                          |
| Run the IMLC Inquire Archive function\.<br><br>The three records, along with their associated data, can be accessed through this function\.                                                                                                                                                                                                                                                                                                               |      | ![tmp129.jpg](./images/5038295d-5ec6-4168-8a14-50a7524ed0f2.jpeg) |











Archiving through STP 

Overview

Parameter Settings

Transaction Process







Overview

When a record in the back\-office system is archived, the corresponding record in CE must also be archived\. 

The back\-office system sends the transaction's main reference number and other details to CE\.  CE, in turn, receives the data through Auto Process function and archives the relevant record through the STP Archive Data function\.  





![Tzone55](./images/e9629e5b-6110-40a4-a379-be1611aff0d7.jpeg)<span style="color:#008080">NOTE:</span> 

<span style="color:#008080">**The STP Archive Data and the**</span> <span style="color:#008080">**manual**</span> <span style="color:#008080">**Archive Data utilize the same**</span> <span style="color:#008080">**f**</span><span style="color:#008080">**unction, which main program is Trx Manager Archive\. For this function to**</span> <span style="color:#008080">**perform**</span> <span style="color:#008080">**the STP Archive Data process**</span><span style="color:#008080">**,**</span> <span style="color:#008080">**the**</span> <span style="color:#008080">**STP and Attribute transaction component settings are defined**</span><span style="color:#008080">**\.**</span> 

<span style="color:#008080">**CE receives the**</span> <span style="color:#008080">**STP message**</span> <span style="color:#008080">**when the**</span> <span style="color:#008080">**InGapiForm message broker**</span> <span style="color:#008080">**is started\.**</span>





  



Parameter Settings

Defining the STP configurations to archive transactions received via STP involves the following parameter settings:

Extension field

STP template and mapping rule

STP Archive Data function





Log on the CE Utility as an Operator user and configure the following settings\.



| Do the following \. \. \. |
| :------------------------ |



| Extension Field<br><br>Run the DB Dictionary function from the Maintenance function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_208.jpg](./images/23d3b4bc-b055-4dcb-885b-ea9097e64bdd.jpeg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :------------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Access the Reformat tab on the DB Dictionary function window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_209.jpg](./images/844e0ae1-e8db-406b-8345-88f21f36206a.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Add an extension field or tag which is to be used for storing module details sent from the back\-office system:<br><br>Name: Module<br><br>DB Type: VARCHAR<br><br>Length: 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![CEv3_210.jpg](./images/18e77cc6-9404-47be-b7cd-7e1fe6ed4e3c.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| STP Mapping<br><br>Run the STP Mapping function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_212.jpg](./images/dff8cd4b-fc15-4599-a89f-1df195d067d0.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Create the Archiving template\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Template ID and Template Description:</span> <span style="color:#008080">ARCHIVE</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEv3_213.jpg](./images/ddfb69ef-fa04-42e9-8a42-48165a0b4025.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Add the following Receive tags, which pertain to field details of the transaction from the back\-office system:<br><br>Module, which pertains to the transaction module <br><br>CEMainRef, which pertains to the main reference number of the transaction<br><br>CustId, which refers to the Customer or Company Id                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |      | ![CEv3_214.jpg](./images/e0d3ccc7-79bd-4684-8db6-a20c4f0de964.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Create an STP mapping rule and map the template tags to the relevant fields:<br><br>CEMainRef: C\_MAIN\_REF<br><br>CustId: C\_UNIT\_CODE <br><br>Module tag: C\_MODULE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      | ![CEv3_215.jpg](./images/992bf96c-817b-4f1d-afd9-6067f0be27e1.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| STP Setting<br><br>Run the STP Setting function from the System Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEv3_216.jpg](./images/b59f9982-51a6-4c2a-a571-ac7d84f1c990.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Access the Assign Function tab for the Incoming Message STP type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |      | ![CEv3_218.jpg](./images/f6c01f8e-e287-4c01-bc9d-4793be89190a.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Select the relevant message type \(i\.e\., the defined STP template\)\.<br><br>Assign the function that is to process the STP message through the stp\.setFunc method\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Transaction function: IMLC Archive Data</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span><br><br><span style="color:#008080">Code:</span><br><br><span style="color:#008080">stp\.setFunc\("IMLC Archive Data", "Import Letters of Credit"\)</span>                                                                                                                                                                                                                                                                |      | ![CEv3_219.jpg](./images/1334524a-ad3c-46c9-a138-ed6fce2562f3.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Transaction Function<br><br>Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![CEv3_168.jpg](./images/a152d209-0a08-457d-a7a6-34945823ea78.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Access the module and function group for which the Archive Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_169.jpg](./images/1692af50-12fe-4b7b-ad56-9229b43654a5.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Access or create the Archive Data function, which is used for archiving the received STP message\.<br><br>For the required parameter settings, refer to Chapter Four > Archive Data Function > Parameter Settings\. <br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Archive Data</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Only one function is used for both STP archiving and</span> <span style="color:#008080">manual archiving</span> <span style="color:#008080">processes: the</span> <span style="color:#008080">IMLC Archive Data</span> <span style="color:#008080">function, which</span> <span style="color:#008080">utilizes the Trx Manager Archive main program\.</span>  |      | ![CEv3_170.jpg](./images/c6d19196-e1e6-4e2a-a9be-8a65298b0028.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| Define the STP settings for this function through the STP function component\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_173.jpg](./images/9f19b57d-81ef-4b4d-be42-753c0c682330.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                            |
| <u><span style="color:#008080">**EXAMPLE**</span></u>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_174.jpg](./images/3e183186-39dc-45b5-879e-22e86676e328.jpeg) |







Transaction Process



| EXAMPLE: |
| :------- |



| Send an STP message to CE\.                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![tmp130.jpg](./images/98339d5d-8b57-4b67-8b0a-b9cb5c2e4d1a.jpeg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :----------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                                          |
| Run the Batch Manager function and display the Message Broker task manager\.  Make sure that the InGapiForm subtask has been started\.<br><br>Check the STP Log: The STP message is received successfully\. <br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp131.jpg](./images/4955201e-6315-41b1-9bb9-ffd032056e4d.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                                          |
| Run the IMLC Inquire Archive function\.<br><br>The record, along with its associated data, can be accessed through this function\.                                                                                                                                                                                                                                                                                                         |      | ![tmp132.jpg](./images/df21e9b3-7d7c-490d-8d2a-2b56314d46fc.jpeg) |















Sample Archiving JSP and JS Files

IMLC\_ArchiveCriteria\.jsp

IMLC\_ViewArchive\.jsp

IMLC\_ViewArchive\_Function\.JS

IMLC\_ViewArchive\_Event\.JS



IMLC\_ArchiveCriteria\.jsp





**\(Start of Code\)**



<%\-\-

/\*\*

 \* $Id: IMLC\_ArchiveCriteria\.jsp,v 1\.5 2013/12/31 02:41:03 HelenLiu Exp $

 \*

 \* @module: Import Letters of Credit \(IMLC\)

 \* @function: Archive

 \*/

\-\-%>

<%@ taglib uri = "/EXIMTAGS" prefix = "EXIMTAGS"%>



<table>

 <tr>

 <td class="FldLabel">Our Reference Number</td>

 <td><select name="OP1" id="OP1" class="CHAR\_O" style="width:170px">

 <option value="like">Contains</option>

 <option value="=">Equal to</option>

 <option value="<=">Less than or equal to</option>

 <option value=">=">More than or equal to</option>

 <option value="<">Less than</option>

 <option value=">">More than</option>

 </select></td>

 <td><input name="OP2" type="text" class="CHAR\_O" id="OP2" title="Our Reference Number" size="35" maxlength="16" style="width:250px"></td>

 <td><select name="OP3" id="OP3" class="CHAR\_O">

 <option value="AND">And</option>

 <option value="OR">Or</option>

 </select></td>

 </tr> 

 <tr>

 <td class="FldLabel">Applicant Name</td>

 <td><select name="OP4" id="OP4" class="CHAR\_O" style="width:170px">

 <option value="like">Contains</option>

 <option value="=">Equal to</option>

 <option value="<=">Less than or equal to</option>

 <option value=">=">More than or equal to</option>

 <option value="<">Less than</option>

 <option value=">">More than</option>

 </select></td>

 <td><input name="OP5" type="text" class="CHAR\_O" id="OP5" size="35" maxlength="16" style="width:250px"></td>

 <td><select name="OP6" id="OP6" class="CHAR\_O">

 <option value="AND">And</option>

 <option value="OR">Or</option>

 </select></td>

 </tr> 

 <tr>

 <td class="FldLabel">Beneficiary Name</td>

 <td><select name="OP7" id="OP7" class="CHAR\_O" style="width:170px">

 <option value="like">Contains</option>

 <option value="=">Equal to</option>

 <option value="<=">Less than or equal to</option>

 <option value=">=">More than or equal to</option>

 <option value="<">Less than</option>

 <option value=">">More than</option>

 </select></td>

 <td><input name="OP8" type="text" class="CHAR\_O" id="OP8" size="35" maxlength="35" style="width:250px"></td>

 <td><select name="OP9" id="OP9" class="CHAR\_O">

 <option value="AND">And</option>

 <option value="OR">Or</option>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Create Date</td>

 <td><select name="OP10" id="OP10" class="CHAR\_O" style="width:170px">

 <option value="like">Contains</option>

 <option value="=">Equal to</option>

 <option value="<=">Less than or equal to</option>

 <option value=">=">More than or equal to</option>

 <option value="<">Less than</option>

 <option value=">">More than</option>

 </select></td>

 <td><input name="OP11" type="text" class="DATE\_O" id="OP11" size="35" maxlength="35" style="width:250px"></td>

 <td>&nbsp;</td>

 </tr> 

</table>



**\(End of Code\)**





IMLC\_ViewArchive\.jsp





**\(Start of Code\)**



<%\-\-

/\*\*

 \* $Id: IMLC\_ViewArchive\.jsp,v 1\.6 2013/12/31 02:45:47 Helen Exp $

 \*

 \* @module: Import Letters of Credit \(IMLC\)

 \* @function: View Archive

 \*/

\-\-%>

<%@ taglib uri = "/EXIMTAGS" prefix = "EXIMTAGS"%>

<%@ taglib uri = "/CETAGS" prefix = "CETAGS"%>



<EXIMTAGS:IncludeFile filePath="\.\./JS/IMLC\_ViewImpLc\_Function\.js"/>

<EXIMTAGS:IncludeFile filePath="\.\./JS/IMLC\_ViewImpLc\_Event\.js"/>

<EXIMTAGS:IncludeFile filePath="\.\./JS/IMLC\_BaseFunc\.js"/>

<input name="CURRNT\_STATUS" type="hidden" class="CHAR\_O" id="CURRNT\_STATUS" title="Current Status" value="">

<input name="NXT\_STATUS" type="hidden" class="CHAR\_O" id="NXT\_STATUS" title="Next Status" value="">

<input name="C\_MAIN\_REF" type="hidden" class="CHAR\_O" id="C\_MAIN\_REF" title="CE Main Reference" value="">

<input name="ACPT\_REJ" type="hidden" class="CHAR\_O" id="ACPT\_REJ" title="Accept or Reject Application" value="">

<input name="REASON\_FOR\_REJ" type="hidden" class="CHAR\_O" id="REASON\_FOR\_REJ" title="Reason for Rejection" value="">

<input name="LC\_BALA" type="hidden" class="AMT\_O" id="LC\_BALA" title="LC Balance" value="">

<input name="BK\_MAIN\_REF" type="hidden" class="CHAR\_O" id="BK\_MAIN\_REF" title="Bank Main Reference" value="">

<input name="PARENT\_MAIN\_REF" type="hidden" class="CHAR\_O"id="PARENT\_MAIN\_REF" title="Parent Main Reference" value="">

<div id="ViewImgLinkDiv" title="Attachment" style="display:none" >

<span><a href="\#" id="ViewImgLink">Hide Image\(s\)</a></span>

<div id="ViewImgDiv" title="Attachment" style="display:none" >

<%@ include file="\.\./\.\./\.\./\.\./include/SysViewImage\.jsp" %>

</div>

</div>

<div id="0\_div" class="Tab" title="Main">

 <table>

 <tbody>

 <tr>

 <td class="FldLabel">LC Number</td>

 <td><input name="LC\_NO" type="text" class="CHAR\_P" id="LC\_NO" title="LC Number" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Drawing Ref\. No\.</td>

 <td><input name="DRAW\_NO" type="text" class="CHAR\_P" id="DRAW\_NO" title="Drawing Ref\. No\." size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amendment No\.</td>

 <td><input name="NO\_OF\_AMD" type="text" class="INT\_P" id="NO\_OF\_AMD" title="Number of Amendment" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Drawing No\.</td>

 <td><input name="NO\_OF\_DRAW" type="text" class="INT\_P" id="NO\_OF\_DRAW" title="Drawing No\." size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Date of Application</td>

 <td><input name="ISSUE\_DT" type="text" class="DATE\_P" id="ISSUE\_DT" title="Date of Application" size="10" maxlength="10"></td>

 </tr>

 <tr>

 <td class="FldLabel">Our Ref Number</td>

 <td><input name="CUST\_NO" type="text" class="CHAR\_P" id="CUST\_NO" title="Our Ref Number" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Type of LC</td>

 <td><select name="FORM\_OF\_LC" id="FORM\_OF\_LC" class="CHAR\_P" title="Type of LC">

 <EXIMTAGS:FldConv fldName="FORM\_OF\_LC" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">LC Currency</td>

 <td><select name="LC\_CCY" id="LC\_CCY" class="CHAR\_P" title="LC Currency">

 <EXIMTAGS:DropDownElement elementType="CCY"/>

 <option value="" selected>PLEASE SELECT</option>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">LC Amount</td>

 <td><input name="LC\_AMT" type="text" class="AMT\_P" id="LC\_AMT" title="LC Amount" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tolerance \- Specification % \+ / \-</td>

 <td><select name="TOL\_SPEC" id="TOL\_SPEC" class="CHAR\_O" title="Tolerance \- Specification % \+ / \-">

 <EXIMTAGS:FldConv fldName="TOL\_SPEC" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Positive tolerance</td>

 <td><input name="POS\_TOL" type="text" class="INT\_P" id="POS\_TOL" title="Positive tolerance" size="2" maxlength="2"></td>

 </tr>

 <tr>

 <td class="FldLabel">Negative tolerance</td>

 <td><input name="NEG\_TOL" type="text" class="INT\_P" id="NEG\_TOL" title="Negative tolerance" size="2" maxlength="2"></td>

 </tr>

 <tr>

 <td class="FldLabel">Total Exposure</td>

 <td><input name="TTL\_EXPOE" type="text" class="AMT\_P" id="TTL\_EXPOE" title="Total Exposure" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Additional Amounts Covered</td>

 <td><textarea name="ADD\_AMT\_COVR" cols="35" rows="4" class="CHAR\_" id="ADD\_AMT\_COVR" title="Additional Amounts Covered"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">Available By</td>

 <td><select name="AVAL\_BY" id="AVAL\_BY" class="CHAR\_M" title="Available By">

 <EXIMTAGS:FldConv fldName="AVAL\_BY" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="MIX\_PAY\_BT" type="button" id="MIX\_PAY\_BT" title="Mixed Payment Button" value="Mixed Payment" onClick="ShowDiv\(\)"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days / Type</td>

 <td><input name="TENOR\_DAYS" type="text" class="INT\_P" id="TENOR\_DAYS" title="Tenor Days" size="3" maxlength="3">

 <select name="TENOR\_TYPE" id="TENOR\_TYPE" class="CHAR\_P" title="Tenor Type">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 </td>

 </tr>

 <tr>

 <td class="FldLabel">Deferred Payment Terms</td>

 <td><textarea name="DEF\_PMT\_TERM" cols="35" rows="4" class="CHAR\_P" id="DEF\_PMT\_TERM" title="Deferred Payment Terms"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">Drafts At</td>

 <td><textarea name="DRAFTS\_AT" cols="35" rows="3" class="CHAR\_P" id="textarea2" title="Drafts At"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">Mixed Payment Details</td>

 <td><textarea name="MIX\_PMT\_DETL" cols="35" rows="4" class="CHAR\_P" id="MIX\_PMT\_DETL" title="Mixed Payment Details"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">SWIFT Messages</td>

 <td><select name="SWIFT\_MSG" id="SWIFT\_MSG" class="CHAR\_O" title="SWIFT Messages">

 <option value="" selected>PLEASE SELECT</option>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Advice Type</td>

 <td><select name="ADV\_TYPE" id="ADV\_TYPE" class="CHAR\_O" title="Advice Type">

 <option value="" selected>PLEASE SELECT</option>

 </select></td>

 </tr>

 </tbody>

 </table>

</div>

<div id="1\_div" class="Tab" title="Parties">

 <table>

 <tbody>

 <tr>

 <td colspan="2" class="HeadingBg">Beneficiary</td>

 </tr>

 <tr>

 <td class="FldLabel">Name</td>

 <td><input name="BENE\_NM" type="text" class="CHAR\_P" id="BENE\_NM" title="Beneficiary Name" size="35" maxlength="35">

 <input name="BENE\_ID" type="hidden" class="CHAR\_O" id="BENE\_ID" title="Beneficiary ID" value=""></td>

 </tr>

 <tr>

 <td class="FldLabel">Location</td>

 <td><input name="BENE\_ADD1" type="text" class="CHAR\_P" id="BENE\_ADD1" title="Beneficiary Location" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">City</td>

 <td><input name="BENE\_ADD2" type="text" class="CHAR\_P" id="BENE\_ADD2" title="Beneficiary City" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Country</td>

 <td><input name="BENE\_ADD3" type="text" class="CHAR\_P" id="BENE\_ADD3" title="Beneficiary Country" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">Applicant</td>

 </tr>

 <tr>

 <td class="FldLabel">Name</td>

 <td><input name="APPL\_NM" type="text" class="CHAR\_P" id="APPL\_NM" title="Applicant Name" size="35" maxlength="35">

 <input name="APPL\_ID" type="hidden" class="CHAR\_O" id="APPL\_ID" title="Applicant ID" value="">

 </td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">Beneficiary Bank</td>

 </tr>

 <tr>

 <td class="FldLabel">SWIFT Address</td>

 <td><input name="BENE\_BK\_SW\_ADD" type="text" class="CHAR\_P" id="BENE\_BK\_SW\_ADD" title="Beneficiary Bank SWIFT Address" size="11" maxlength="11"></td>

 </tr>

 <tr>

 <td class="FldLabel">Name</td>

 <td><input name="BENE\_BK\_NM" type="text" class="CHAR\_P" id="BENE\_BK\_NM" title="Beneficiary Bank Name" size="35" maxlength="35">

 <\!\-\-<input name="BENE\_BK\_ID\_BT" type="button" class="CHAR\_P" id="BENE\_BK\_ID\_BT" title="Beneficiary Bank ID Button" value="\.\.\.">\-\->

 <input name="BENE\_BK\_ID" type="hidden" class="CHAR\_O" id="BENE\_BK\_ID" title="Beneficiary Bank ID" value=""></td>

 </tr>

 <tr>

 <td class="FldLabel">Location</td>

 <td><input name="BENE\_BK\_ADD1" type="text" class="CHAR\_P" id="BENE\_BK\_ADD1" title="Beneficiary Bank Location" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">City</td>

 <td><input name="BENE\_BK\_ADD2" type="text" class="CHAR\_P" id="BENE\_BK\_ADD2" title="Beneficiary Bank City" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Country</td>

 <td><input name="BENE\_BK\_ADD3" type="text" class="CHAR\_P" id="BENE\_BK\_ADD3" title="Beneficiary Bank Country" size="35" maxlength="35"></td>

 </tr>

 <td colspan="2" class="HeadingBg">For Account Of</td>

 </tr><tr>

 <td class="FldLabel">Name</td>

 <td><input name="FOR\_AC\_OF\_NM" type="text" class="CHAR\_P" id="FOR\_AC\_OF\_NM" title="Account Of Name" size="35" maxlength="35">

 <input name="FOR\_AC\_OF\_ID" type="hidden" class="CHAR\_O" id="FOR\_AC\_OF\_ID" title="Account Of ID" value=""></td>

 </tr>

 <tr>

 <td class="FldLabel">Location</td>

 <td><input name="FOR\_AC\_OF\_ADD1" type="text" class="CHAR\_P" id="FOR\_AC\_OF\_ADD1" title="Account Of Location" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">City</td>

 <td><input name="FOR\_AC\_OF\_ADD2" type="text" class="CHAR\_P" id="FOR\_AC\_OF\_ADD2" title="Account Of  City" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td class="FldLabel">Country</td>

 <td><input name="FOR\_AC\_OF\_ADD3" type="text" class="CHAR\_P" id="FOR\_AC\_OF\_ADD3" title="Account Of Country" size="35" maxlength="35"></td>

 </table>

</div>

<div id="2\_div" class="Tab" title="Shipment / Expiry">

 <table>

 <tr>

 <td class="FldLabel">Date of Expiry</td>

 <td><input name="EXPIRY\_DT" type="text" class="DATE\_P" id="EXPIRY\_DT" title="Date of Expiry" size="10" maxlength="10"></td>

 </tr>

 <tr>

 <td class="FldLabel">Place of Expiry</td>

 <td><input name="EXPIRY\_PLC" type="text" class="CHAR\_P" id="EXPIRY\_PLC" title="Place of Expiry" size="29" maxlength="29"></td>

 </tr>

 <tbody>

 <tr>

 <td class="FldLabel">Latest Shipment Date</td>

 <td><input name="LTST\_SHIP\_DT" type="text" class="DATE\_P" id="LTST\_SHIP\_DT" title="Latest Shipment Date" size="10" maxlength="10"></td>

 </tr>

 <tr>

 <td class="FldLabel">Shipment Period</td>

 <td><textarea name="SHIP\_PRD" cols="65" rows="6" class="CHAR\_P" id="SHIP\_PRD" title="Shipment Period"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">Partial Shipment</td>

 <td><select name="PARTIAL\_SHIP" id="PARTIAL\_SHIP" class="CHAR\_M" title="Partial Shipment">

 <EXIMTAGS:FldConv fldName="PARTIAL\_SHIP" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Transhipment</td>

 <td><select name="TNSHIP" id="TNSHIP" class="CHAR\_M" title="Transhipment">

 <EXIMTAGS:FldConv fldName="TNSHIP" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Ship From</td>

 <td><input name="LOAD\_PLACE" type="text" class="CHAR\_P" id="LOAD\_PLACE" title="Ship From" size="65" maxlength="65"></td>

 </tr>

 <tr>

 <td class="FldLabel">Port of Loading</td>

 <td><input name="LOAD\_PORT" type="text" class="CHAR\_P" id="LOAD\_PORT" title="Port of Loading" size="65" maxlength="65"></td>

 </tr>

 <tr>

 <td class="FldLabel">Port of Discharge</td>

 <td><input name="DEST\_PORT" type="text" class="CHAR\_P" id="DEST\_PORT" title="Port of Discharge" size="65" maxlength="65"></td>

 </tr>

 <tr>

 <td class="FldLabel">Ship To</td>

 <td><input name="DEST\_PLACE" type="text" class="CHAR\_P" id="DEST\_PLACE" title="Ship To" size="65" maxlength="65"></td>

 </tr>

 <tr>

 <td class="FldLabel">Description of Goods</td>

 <td><textarea name="GOODS\_DESC" cols="65" rows="100" class="CHAR\_P" id="GOODS\_DESC" style="height:250px " title="Mixed Payment Details"></textarea></td>

 </tr>

 </tbody>

 </table>

</div>

<div id="3\_div" class="Tab" title="Documents">

 <table>

 <tbody>

 <tr>

 <td class="FldLabel">Incoterms</td>

 <td><select name="INCOTERMS" id="INCOTERMS" class="CHAR\_P" title="Incoterms">

        <EXIMTAGS:FldConv fldName="INCOTERMS" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Incoterms Instructions</td>

 <td><input name="INCOTERMS\_INSTR" type="text" class="CHAR\_P" id="INCOTERMS\_INSTR" title="Incoterms Instructions" size="50" maxlength="50"></td>

 </tr>

 <tr>

 <td class="FldLabel">Documents to be Presented</td>

 <td><textarea name="DOC\_PRES" cols="65" rows="100" class="CHAR\_P" id="DOC\_PRES" style="height:250px " title="Documents to be Presented"></textarea>

 </td>

 </tr>

 <tr>

 <td class="FldLabel">Presentation Days</td>

 <td><input name="PRES\_DAYS" type="text" class="INT\_P" id="PRES\_DAYS" title="Presentation Days" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Presentation Period Event</td>

 <td><select name="PRES\_PRD\_EVENT" id="PRES\_PRD\_EVENT" class="CHAR\_M" title="Presentation Period Event">

 <EXIMTAGS:FldConv fldName="PRES\_PRD\_EVENT" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Presentation Period</td>

 <td><textarea name="PRES\_PRD\_TXT" cols="35" rows="4" class="CHAR\_P" id="PRES\_PRD\_TXT" title="Presentation Period"></textarea></td>

 </tr>

 </tbody>

 </table>

</div>

<div id="4\_div" class="Tab" title="Instructions">

 <table>

 <tbody>

 <tr>

 <td class="FldLabel">Confirmation Instruction</td>

 <td><select name="CONF\_INSTR" id="CONF\_INSTR" class="CHAR\_M" title="Confirmation Instruction">

 <EXIMTAGS:FldConv fldName="CONF\_INSTR" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Additional Conditions</td>

 <td><textarea name="ADDIT\_CONDITION" cols="65" rows="100" class="CHAR\_P" id="ADDIT\_CONDITION" style="height:250px " title="Additional Conditions"></textarea></td>

 </tr>

 <tr>

 <td class="FldLabel">Charge Account</td>

 <td><select name="CHG\_AC\_CCY" id="CHG\_AC\_CCY" class="CHAR\_P" title="Charge Currency">

 <EXIMTAGS:DropDownElement elementType="CCY"/>

 <option value="" selected>PLEASE SELECT</option>

 </select>

 <input name="CHG\_AC" type="text" class="CHAR\_P" id="CHG\_AC" title="Charge Account" size="20" maxlength="20">

 </td>

 </tr>

 <tr>

 <td class="FldLabel">Principle Account</td>

 <td><select name="PRINC\_CCY" id="PRINC\_CCY" class="CHAR\_P" title="Principle Currency">

 <EXIMTAGS:DropDownElement elementType="CCY"/>

 <option value="" selected>PLEASE SELECT</option>

 </select>

 <input name="PRINC\_AC" type="text" class="CHAR\_P" id="PRINC\_AC" title="Principle Account" size="20" maxlength="20">

 </td>

 </tr>

 <tr>

 <td class="FldLabel">Charges</td>

 <td><select name="CHG\_FLAG" id="CHG\_FLAG" class="CHAR\_P" title="Charges">

 <EXIMTAGS:FldConv fldName="CHG\_FLAG" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Forward Cover</td>

 <td><select name="FWD\_COVER" id="FWD\_COVER" class="CHAR\_O" title="Forward Cover">

 <EXIMTAGS:FldConv fldName="FWD\_COVER" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Customer Instructions</td>

 <td><textarea name="CUST\_INSTR" cols="35" rows="15" class="CHAR\_P" id="CUST\_INSTR" style="height:250px " title="Customer Instructions"></textarea></td>

 </tr>

 </tbody>

 </table>

</div>

<div id="MixedPaymentDetail" class="hidden" onMouseDown="mousedown\(this\)" title="Mixed Payment Detail" style="position:absolute;left:562px; top:2807px; width:450px; height:450px; overflow:auto; background:\#CCFF33; display:none">

 <table>

 <tbody>

 <tr>

 <td class="HeadingBg style1">1</td>

 <td align="right" class="HeadingBg"><input name="CLOSE" type="button" id="CLOSE" title="CLOSE" value="CLOSE" onClick="HideDiv\(\)"></td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG1" id="SDA\_FLAG1" class="CHAR\_O" title="Payment Type 1">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG1" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER1" type="text" class="INT\_P" id="PAY\_PER1" title="Percentage1" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT1" type="text" class="AMT\_P" id="PAY\_AMT1" title="Amount1" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS1" type="text" class="INT\_P" id="TENOR\_DAYS1" title="Tenor Days1" size="3" maxlength="3">

 <select name="TENOR\_TYPE1" id="TENOR\_TYPE1" class="CHAR\_O" title="Tenor Type1">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE1" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_21" type="text" class="CHAR\_P" id="TENOR\_TYPE\_21" title="Tenor Type\_2 1" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">2</td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG2" id="SDA\_FLAG2" class="CHAR\_O" title="Payment Type 2">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG2" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER2" type="text" class="INT\_P" id="PAY\_PER2" title="Percentage2" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT2" type="text" class="AMT\_P" id="PAY\_AMT2" title="Amount2" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS2" type="text" class="INT\_P" id="TENOR\_DAYS2" title="Tenor Days2" size="3" maxlength="3">

 <select name="TENOR\_TYPE2" id="TENOR\_TYPE2" class="CHAR\_O" title="Tenor Type2">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE2" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_22" type="text" class="CHAR\_P" id="TENOR\_TYPE\_22" title="Tenor Type\_2 2" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">3</td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG3" id="SDA\_FLAG3" class="CHAR\_O" title="Payment Type3">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG3" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER3" type="text" class="INT\_P" id="PAY\_PER3" title="Percentage3" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT3" type="text" class="AMT\_P" id="PAY\_AMT3" title="Amount3" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS3" type="text" class="INT\_P" id="TENOR\_DAYS3" title="Tenor Days3" size="3" maxlength="3">

 <select name="TENOR\_TYPE3" id="TENOR\_TYPE3" class="CHAR\_O" title="Tenor Type3">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE3" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_23" type="text" class="CHAR\_P" id="TENOR\_TYPE\_23" title="Tenor Type\_2 3" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">4</td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG4" id="SDA\_FLAG4" class="CHAR\_O" title="Payment Type 4">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG4" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER4" type="text" class="INT\_P" id="PAY\_PER4" title="Percentage4" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT4" type="text" class="AMT\_P" id="PAY\_AMT4" title="Amount4" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS4" type="text" class="INT\_P" id="TENOR\_DAYS4" title="Tenor Days4" size="3" maxlength="3">

 <select name="TENOR\_TYPE4" id="TENOR\_TYPE4" class="CHAR\_O" title="Tenor Type4">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE4" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_24" type="text" class="CHAR\_P" id="TENOR\_TYPE\_24" title="Tenor Type\_2 4" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">5</td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG5" id="SDA\_FLAG5" class="CHAR\_O" title="Payment Type 5">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG5" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER5" type="text" class="INT\_P" id="PAY\_PER5" title="Percentage5" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT5" type="text" class="AMT\_P" id="PAY\_AMT5" title="Amount5" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS5" type="text" class="INT\_P" id="TENOR\_DAYS5" title="Tenor Days5" size="3" maxlength="3">

 <select name="TENOR\_TYPE5" id="TENOR\_TYPE5" class="CHAR\_O" title="Tenor Type 5">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE5" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_25" type="text" class="CHAR\_P" id="TENOR\_TYPE\_25" title="Tenor Type\_2 5" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="HeadingBg">6</td>

 </tr>

 <tr>

 <td class="FldLabel">Payment Type</td>

 <td><select name="SDA\_FLAG6" id="SDA\_FLAG6" class="CHAR\_O" title="Payment Type 6">

 <EXIMTAGS:FldConv fldName="SDA\_FLAG6" smType="false" emptyValue="" blankOption="TRUE"/>

 </select></td>

 </tr>

 <tr>

 <td class="FldLabel">Percentage</td>

 <td><input name="PAY\_PER6" type="text" class="INT\_P" id="PAY\_PER6" title="Percentage6" size="3" maxlength="3"></td>

 </tr>

 <tr>

 <td class="FldLabel">Amount</td>

 <td><input name="PAY\_AMT6" type="text" class="AMT\_P" id="PAY\_AMT6" title="Amount6" size="24" maxlength="24"></td>

 </tr>

 <tr>

 <td class="FldLabel">Tenor Days</td>

 <td><input name="TENOR\_DAYS6" type="text" class="INT\_P" id="TENOR\_DAYS6" title="Tenor Days6" size="3" maxlength="3">

 <select name="TENOR\_TYPE6" id="TENOR\_TYPE6" class="CHAR\_O" title="Tenor Type6">

 <EXIMTAGS:FldConv fldName="TENOR\_TYPE6" smType="false" emptyValue="" blankOption="TRUE"/>

 </select>

 <input name="TENOR\_TYPE\_26" type="text" class="CHAR\_P" id="TENOR\_TYPE\_26" title="Tenor Type\_2 6" size="35" maxlength="35"></td>

 </tr>

 <tr>

 <td colspan="2" class="FldLabel">&nbsp;</td>

 </tr>

 <tr>

 <td class="FldLabel">Total Amount</td>

 <td><input name="TTL\_PAY\_AMT" type="text" class="AMT\_P" id="PAY\_AMT62" title="Amount6" size="24" maxlength="24"></td>

 </tr>

 </tbody>

 </table>

</div>



**\(End of Code\)**





IMLC\_ViewArchive\_Function\.JS





**\(Start of Code\)**



// $Id: IMLC\_ViewArchive\_Function\.js,v 1\.6 2013/12/31 03:01:08 helenliu Exp $

function Get\_CURRNT\_STATUS\(\)\{

 try \{

 //        setFldValue\("CURRNT\_STATUS","Issued LC"\);

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Function", e\);

 \}

\}



function Get\_NXT\_STATUS\(\)\{

 try \{

 //        setFldValue\("NXT\_STATUS", ""\);

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Function", e\);

 \}

\}



**\(End of Code\)**





IMLC\_ViewArchive\_Event\.JS





**\(Start of Code\)**



// $Id: IMLC\_ViewArchive\_Event\.js,v 1\.6 2013/12/31 03:01:08 HelenLiu Exp $

function OnInit\(\)\{

 try \{

 if \(SYS\_FUNCTION\_TYPE == "EC" :: SYS\_FUNCTION\_TYPE == "RE" :: SYS\_FUNCTION\_TYPE == "IQ" :: SYS\_FUNCTION\_TYPE == "DM"\) \{

 SYS\_CONFIRM\_FLAG = true;

 GetImageList\(\);

 \}

 else \{

 if \(SYS\_ERROR\.length == 0\) \{

 SYS\_CONFIRM\_FLAG = false;

 InitValue\(\);

 \}

 \}

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Event", e\);

 \}

\}



function InitValue\(\)\{

 try \{

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Event", e\);

 \}

\}



function ChkTrxData\(\)\{

 try \{

 return true;

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Event", e\);

 \}

\}



function ConfirmTrx\(\)\{

 try \{

 //Get\_CURRNT\_STATUS\(\);

 //Get\_NXT\_STATUS\(\);

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Event", e\);

 \}

\}



function InitFldEvt\(\)\{

 try \{

 \} 

 catch \(e\) \{

 showExcpt\("IMLC\_ViewArchive\_Event", e\);

 \}

\}



**\(End of Code\)**



Glossary



Glossary







a





| ***Application Server***    | Server where the CE system is actually deployed and where CE processes the business logic and parameter operations\.                                   |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                             |                                                                                                                                                        |
| ***Archiving***             | The process of transferring transaction records from the Transaction Database to the Backup Database\.                                                 |
|                             |                                                                                                                                                        |
| ***Auto Archiving***        | Mode of archiving in which records are automatically archived by batch according to a set of defined criteria\.  This is also called Batch Archiving\. |
|                             |                                                                                                                                                        |
| ***Archive Data Function*** | Function used for archiving records\.                                                                                                                  |





B





| ***Batch Archiving*** | See Auto Archiving\.                                            |
| --------------------- | --------------------------------------------------------------- |
|                       |                                                                 |
| ***Business Unit***   | A processing center or a branch unit of a bank\-country group\. |





C





| ***CE Utility***                 | Short for Customer Enterprise Utility Workbench\.  This is the main tool for building parameters in CE\.                                                                                                                         |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                  |                                                                                                                                                                                                                                  |
| ***Customer Enterprise \(CE\)*** | The Eximbills business\-to\-business \(B2B\) solution that provides bank customers with a convenient and secure single window for processing and inquiring on all their trade finance, open account, and payments transactions\. |





D





| ***Database*** | An application used for the management, storage, and retrieval of data\.                                                                           |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
|                |                                                                                                                                                    |
| ***Document*** | Also referred to as form\.  It is one of the types of output that can be generated in HTML, PDF, WORD, or EXCEL format by a transaction function\. |



E





| ***End\-user*** | The actual user running the CE business functions\.                                                                                 |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
|                 |                                                                                                                                     |
| ***Eximbills*** | The flagship product of China Systems, which provides support for advanced e\-commerce, open account, and trade\-related services\. |



F





| ***Field***    | The smallest unit that can hold data\.                                                                                                                                                       |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                |                                                                                                                                                                                              |
| ***Function*** | A unified set of elements, operations, and configurations that produce a target setting, process, and/or output\. This typically refers to a CE Utility function or a transaction function\. |

I





| ***Inquire Archived Data Function*** | Function used for inquiring into records that are stored in the Archive file\. |
| ------------------------------------ | ------------------------------------------------------------------------------ |





M





| ***Manual Archiving*** | Mode of archiving in which records are manually archived per module according to a set of defined criteria\.  In addition, records received via STP can also be archived through this mode\.                                                                     |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                        |                                                                                                                                                                                                                                                                  |
| ***Meta Data***        | The parameter data, or simply parameters, that are defined in the CE Utility\.                                                                                                                                                                                   |
|                        |                                                                                                                                                                                                                                                                  |
| ***Module***           | A group of functions that perform interrelated processes and operate under a general principle or objective \(e\.g\., a system module, which is essential to system processes; a business or transaction module, which pertains to a bank service or product\)\. |





P





| ***Parameter***       | Any user\-controlled configuration that defines a factor or logic within a set of interrelated operations; performs a specific action in a group of processes; or produces a categorical result or setting\. |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                       |                                                                                                                                                                                                              |
| ***Parameter Files*** | See XML*\.*                                                                                                                                                                                                  |









R





| ***Recovery***                       | The process of retrieving archived records from the Backup Database\.                                          |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
|                                      |                                                                                                                |
| ***Restore Archived Data Function*** | Function used for retrieving transactions from the Backup Database, and adding these back to the master file\. |



S





| ***SQL***  | Stands for Structured Query Language\.  This is a standard interactive and programming language for retrieving and updating data in the database\. |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |



X





| ***XML***                    | Stands for Extensible Markup Language\.  This is the format used by CE for the communication between the client \(browser\) and the server\. |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
|                              |                                                                                                                                              |
| ***XML Generator Function*** | The CE Utility function that is used to generate the corresponding XML files for a specific parameter setting\.                              |




-----


