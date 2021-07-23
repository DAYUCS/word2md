---
title: "Archiving and Recovery"
weight: 20
type: docs
description: >
    Archiving and Recovery on CE.
---

![](images/)



| <br>EXIMBILLS © Trade Finance System<br><br>Customer Enterprise Version 3\.3\.6<br><br>Archiving and Recovery<br><br>July 2021                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| *Copyright* *2021* *© China Systems Corporation*<br><br>*All Rights Reserved*<br><br><br><br>*This document is protected by United States Copyright Law and may contain Trade Secrets Information which is proprietary to China Systems Corporation\.  No part of this document may be copied, photocopied, reproduced, translated, distributed, or reduced to any electronic medium or machine\-readable form without prior consent in writing from China Systems Corporation\.  The information in this document may be used only under the terms and conditions of separate China Systems Corporation license agreements\.*<br><br>*Information is subject to change without notice\.  China Systems Corporation makes no warranties, either expressed or implied, with respect to the software herein described as to its quality, performance, including, without limitations to, its fitness for any particular purpose\.*<br><br>*This document may not reflect total system capability at any subsequent date as a result of development\.  It is also possible that it may contain references to facilities not available on your computer system\.  Such references should not be construed to mean that these facilities will necessarily be made available on all types of computer hardware or in all user locations\.*<br><br>*China Systems Corporation accepts no responsibility or liability for any damages or loss of business or revenue due to the use of this document\.*<br><br>*All trademarks, registered trademarks and trade names mentioned in this document are the sole property of their respective holders\.* |
| ORDER MORE EXIMBILLS DOCUMENTATION<br><br>Additional copies of Documentation are available for purchase from China Systems Corporation or through your local EXIMBILLS Support Office\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ![csliit](images/796002d6-753a-4031-9de1-337f3105cdbb.jpeg)<br><br>CHINA SYSTEMS CORPORATION<br><br>Comments may be addressed to:<br><br><u><span style="color:#0000FF">[corporatedocs@chinasystems\.com](mailto:corporatedocs@chinasystems.com)</span></u><br><br>China Systems Corporation Ltd\.<br><br>Corner House, 20 Parliament Street<br><br>Hamilton HM12<br><br>Bermuda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |



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







![Tzone55](images/0918e644-46e2-43c0-9e3b-5bd66a133e34.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">Some features discussed in this manual have been tested and documented based on an older system version\.  Unless otherwise specified, the overall functionality is the same when recreated in the current version\.</span>





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





| ![](images/9154101b-7cef-4b50-b74f-2f69e302bec6.png) |
| :--------------------------------------------------: |

***Figure 2\.*** ***1*** ***CE Utility Folder***



![Tzone55](images/5c1a81bf-92ac-425d-bae1-c49985cfc817.jpeg)<span style="color:#008080">**NOTE:**</span> 

<span style="color:#008080">The default drives defined in the GEN\_XML\_ROOTPATH and GEN\_WEB\_ROOTPATH system parameters are</span> <span style="color:#008080">O:\</span> <span style="color:#008080">and</span> <span style="color:#008080">P:\</span> <span style="color:#008080">respectively\. These drives, if currently not existing, may be created through a batch file\. While</span> <span style="color:#008080">O:\</span> <span style="color:#008080">and</span> <span style="color:#008080">P:\</span><span style="color:#008080">are the default drives for CE, these may be set to any other preferred drive available in the network\.</span> 

<span style="color:#008080">To enable users to use the CE Utility on their own local machines as clients connecting to the CE server: 1\) Install the Java Development Kit \(JDK\) program; 2\) Copy the CE Utility folder; 3\) Create the</span> <span style="color:#008080">JAVA\_HOME</span> <span style="color:#008080">environment variable, which</span> <span style="color:#008080">must</span> <span style="color:#008080">point to this directory:</span> <span style="color:#008080">\[Java Home\]\\[Installed JDK\]</span><span style="color:#008080">\.</span>

<span style="color:#008080">For more information on setting up the CE environment, refer to the CE installation guides</span><span style="color:#008080">*\.*</span> 

<span style="color:#008080">For information on the CE Utility functions, refer to the</span> <span style="color:#008080">*CE Utility Reference*</span> <span style="color:#008080">manuals\.</span>





| **Batch File for Creating the CE Drives**<br><br>The batch file for creating drives contains the following commands:<br><br><br><br>subst O: /d<br><br>subst P: /d<br><br>subst O: C:"\Program Files\IBM\WebSphere\AppServer\profiles\AppSrv01\installedApps\DOCS\-CEV336Node01Cell\CE\.ear\CE\_PARA"<br><br>subst P: C:"\Program Files\IBM\WebSphere\AppServer\profiles\AppSrv01\installedApps\DOCS\-CEV336Node01Cell\CE\.ear\CEWeb\.war" <br><br><br><br>![](images/eb65795d-8f04-4051-ac4f-fa042c8f20fe.png) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |



Accessing the CE Utility

The main program for running the CE Utility is the CEUtility\.bat file, which is found in the CE Utility folder\.



| <span style="color:#000000">**Do the following \. \.**</span> <span style="color:#000000">**\.**</span> |
| ------------------------------------------------------------------------------------------------------- |



| Run the CEUtility batch program to access the CE Utility\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">A shortcut for the CEUtility batch file can be created on the desktop for easy access\.</span>                                                                                                                                                                                                                                                                                                                                                         |      | ![](images/31191e8a-c4b3-4eda-b7e5-b2716628e776.png) |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| The logon window of the CE Utility is displayed\.<br><br>To define the database information, click on the Profile button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![](images/f4c3c29e-3fd4-410a-8f49-4986b1b2b608.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| In the Database Information dialog box that is displayed, specify the required database details and click on the Save button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](images/72f2241a-1a68-4213-8515-abcae13e8062.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| A confirmation message is displayed\. Click on the OK button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](images/dd18c65e-1848-4950-926e-6fbf63c3389a.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">This new data source setting is saved in the</span> <span style="color:#008080">UserInfo\.xml</span> <span style="color:#008080">file in the CE Utility directory\.</span>                                                                                                                                                                                                                                                                                                                                                       |      | ![](images/8947a075-1e03-470c-8c12-6f4a9500b964.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| The relevant username and password may then be specified for logging on the CE Utility\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">For information on defining CE Utility user profiles, refer to the</span> <span style="color:#008080">*CE System Administration Functions*</span> <span style="color:#008080">manual\.</span>                                                                                                                                                                                                                            |      | ![](images/0f6b087e-46a2-460c-8f4f-fbcb0ec5424b.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| The CE Utility window is displayed\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![](images/6ec1d04e-dc76-4a30-8e64-e6873533db11.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                      |
| A function is accessed by opening or double\-clicking on the relevant function group and clicking on the function name\.<br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">A user may only access and utilize the functions assigned to him\.</span>  <span style="color:#008080">For more details, refer to the</span> <span style="color:#008080">*CE Utility Reference*</span><span style="color:#008080">*:*</span> <span style="color:#008080">*User Manager Functions*</span> <span style="color:#008080">documentation</span><span style="color:#008080">*\.*</span> |      | ![](images/4987ed5a-6c46-4962-9818-e1c72e966125.png) |



![Tzone55](images/5ecd37ee-32ac-43ed-a937-912c30a3ed6e.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">It is sometimes necessary to assign a new user name and password when the new database is restored from a backup file\.  Restoring the backup file restores the original user profiles\.</span>

<span style="color:#008080">The new user profiles for the CE Utility \(as well as the CE Security Module\) can be defined during the installation process\.  SQL scripts are run to create these profiles\.  Refer to the CE installation guides for more information\.</span>

Navigating the CE Utility Interface

After logging on, the CE Utility window is displayed and parameters may then be configured\. The functions used for setting up parameters may be accessed by clicking on the function name on the Function menu or by using the shortcut buttons\.

The CE Utility interface also provides ways by which parameters can be created, edited, deleted or linked to other operations: menu bar, toolbar buttons, and popup menu\.





| ![](images/b2e6f408-724c-4a50-903c-648c16559492.png) |
| :--------------------------------------------------: |

***Figure 2\.*** ***2*** ***The CE Utility Interface***





![Tzone55](images/3995faef-a070-4350-96dd-8676c073244e.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">A function is only displayed, and its corresponding button or menu option enabled, if the user has been given the right to access this function\.</span>  <span style="color:#008080">Some options and functions are only available to Super Administrator users, while others are only accessible to Administrator and Operator users\.</span>









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



| ![](images/de0cf386-88e1-4a55-8975-570852323ad4.png) |
| :--------------------------------------------------: |

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



| ![](images/12ce04e1-0c10-4b0a-bc73-b2a209651fa4.png) |
| :--------------------------------------------------: |

***Figure 2\.*** ***4*** ***Basic Toolbar Buttons***





| <span style="color:#000000">**Button**</span> |      | <span style="color:#000000">**Description**</span> |
| :-------------------------------------------: | :--: | :------------------------------------------------: |



| ![](images/19d7078c-62ec-4af0-90b1-f82ca9afe8ef.png) **New**                       |      | This button is used for creating a new parameter or rule\.                          |
| ---------------------------------------------------------------------------------: | ---- | ----------------------------------------------------------------------------------- |
|                                                                                    |      |                                                                                     |
| ![](images/1286d286-4bdd-4713-a33e-f76d971edf0b.png) **Add**                       |      | This button is used for adding a setting for the selected function or parameter\.   |
|                                                                                    |      |                                                                                     |
| ![](images/c87c20c6-5c5e-4dd4-931c-cdea2c35ae42.png) **Save**                      |      | This button is used for storing created or modified settings\.                      |
|                                                                                    |      |                                                                                     |
| ![](images/fa864899-09f3-46e0-b484-8f6b03be13ff.png) **Edit**                      |      | This button is used for editing or modifying existing settings\.                    |
|                                                                                    |      |                                                                                     |
| ![](images/6f861eb9-483d-4d69-9370-d976b810c2cc.png) **Copy**                      |      | This button is used for copying or duplicating a selected setting\.                 |
|                                                                                    |      |                                                                                     |
| ![](images/78b0aad1-857a-405c-a051-101bdf78f14d.png) **Delete**                    |      | This button is used for deleting or removing an existing setting\.                  |
|                                                                                    |      |                                                                                     |
| ![](images/34116576-0444-4019-bf1e-6a03f7276286.png) **Find**                      |      | This button is used for finding an existing setting\.                               |
|                                                                                    |      |                                                                                     |
| ![](images/707f3a1d-05a0-495f-a859-3aa0dc95828c.png) **Close Function**            |      | This button is used for closing a function window\.                                 |
|                                                                                    |      |                                                                                     |
| ![](images/5b326904-751c-43e7-b10a-2d724923160d.png) **Help Topic**                |      | This button is *currently not used\.*                                               |
|                                                                                    |      |                                                                                     |
| ![](images/d1524da5-4d2f-4f50-83c4-dce115ce861d.png) **About Customer Enterprise** |      | This button is used for displaying the version information of Customer Enterprise\. |







**Function Toolbar**

The buttons on this toolbar are shortcuts to some of the functions that are in the Function Group lists of the CE Utility window\. The buttons may also be accessed from the Function menu on the menu bar\.



| ![tmp6387](images/2fbf98f0-e88f-42c0-9c8e-83a962f95975.jpeg) |
| :----------------------------------------------------------: |

***Figure 2\.*** ***5*** ***Function Toolbar Buttons***





| <span style="color:#000000">**Button**</span> |      | <span style="color:#000000">**Description**</span> |
| :-------------------------------------------: | :--: | :------------------------------------------------: |



| ![](images/34c00d5b-fd05-41df-8dc8-a6f463cb86a3.png) **Set System Parameter**               |      | This button is used for accessing the System Parameter function\. The function may also be accessed from the Parameter Manage group in the Function menu\.   |
| ------------------------------------------------------------------------------------------: | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/03c3881d-189f-438d-a431-3694c967f4e8.png) **Manage Component**                   |      | This button is used for accessing the Component Manage function\. The function may also be accessed from the Parameter Manage group in the Function menu\.   |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/5939c3ef-a12b-47ab-aef3-bd92b9bc678f.png) **Calculation**                        |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/677646fc-71dc-4e65-9679-4a28b045b5d4.png) **Module/Event Configuration**         |      | This button is used for accessing the Module & Event function\. The function may also be accessed from the Transaction Function group in the Function menu\. |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/042fc4d8-96ad-4f84-ba96-05bb3a7c82dc.png) **Transaction Function Configuration** |      | This button is used for accessing the Transaction Function\. The function may also be accessed from the Transaction Function group in the Function menu\.    |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/17883a47-517c-436c-829c-9c3d461051f7.png) **Form Set**                           |      | This button is used for accessing the Form function\. The function may also be accessed from the Transaction Function group in the Function menu\.           |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/4f819286-d9c5-41a9-b127-d931fbdd713b.png) **Accounting Rule Setting**            |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/c041d36f-c927-4bf5-9355-72c5aa3f7ef7.png) **Field Conversion**                   |      | This button is used for accessing the Field Conversion function\. The function may also be accessed from the Maintenance group in the Function menu\.        |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/9cd8f075-66b9-43f7-9354-f37adcb85464.png)**Get Data**                            |      | This button is used for accessing the Get Data function\. The function may also be accessed from the Transaction Function group in the Function menu\.       |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/78ee710d-1c85-4dbd-b64f-488456811d4e.png) **Reference Number**                   |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/c53b83b5-32c4-4e19-97eb-36cd65edce5b.png) **Output Device**                      |      | This button is used for accessing the Output Device function\. The function may also be accessed from the System Function group in the Function menu\.       |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/0d212f17-6af2-48c4-a4d2-c1aa2f1927d1.png) **Function Group**                     |      | This button is *currently not used\.*                                                                                                                        |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/30d20a85-a1a7-441d-83e9-ef4f1933f9d9.png) **Clause**                             |      | This button is used for accessing the Clause function\. The function may also be accessed from the Transaction Function group in the Function menu\.         |
|                                                                                             |      |                                                                                                                                                              |
| ![](images/3ede2afd-94e9-4017-ac35-34e829b8bf46.png) **SWIFT**                              |      | This button is used for accessing the SWIFT Config function\. The function may also be accessed from the Transaction Function group in the Function menu\.   |
|                                                                                             |      |                                                                                                                                                              |



| ![](images/adba87db-83ef-4238-88c3-81e1afe7ff58.png) **Queue Manager**               |      | This button is used for accessing the Queue Manager function\. The function may also be accessed from the System Function group in the Function menu\.               |
| -----------------------------------------------------------------------------------: | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/9102a4ca-700a-44aa-a125-23af329102f3.png) **GAPIs Setting**               |      | This button is used for accessing the GAPIs Setting function\. The function may also be accessed from the Transaction Function group in the Function menu\.          |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/ff432c1c-3bfd-4acb-8520-651eeff86730.png) **Time Zone**                   |      | This button is used for setting time zone\. The function may also be accessed from the System Function group in the Function menu\.                                  |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/fc97262f-2da9-43fd-93e5-145a9c4b8a44.png) **STP Setting**                 |      | This button is used for accessing the STP Setting function\. The function may also be accessed from the System Function group in the Function menu\.                 |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/ab72e064-324a-4a0a-984f-65edec9484cc.png) **Message Broker Setting**      |      | This button is used for accessing the Message Broker Setting function\. The function may also be accessed from the Transaction Function group in the Function menu\. |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/a8e7109f-51e8-4171-8ddf-b702bc5d307c.png) **Processing Center**           |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/4ec2d162-d363-4767-8826-1efd031ba17e.png) **Amount Format Setting**       |      | This button is used for accessing the Amount/Rate Format function\. The function may also be accessed from the Transaction Function group in the Function menu\.     |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/d6cbedc4-ada1-43e2-b375-5b8225c654e0.png) **Error Message**               |      | This button is used for accessing the Error Message Config \(CE\) function\. The function may also be accessed from the Maintenance group in the Function menu\.     |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/df9f31a0-f544-43fb-ac01-e9effd67a3d7.png) **Say Total**                   |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/24c57c22-bbbe-4498-9285-93b40f466ba7.png) **Holiday**                     |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/d5ec9cdd-7e27-41a7-be2f-b3470d925f6b.png) **Report**                      |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/ae7ad67c-241c-4cc5-a8c8-0d34400e02e1.png) **Transfer To**                 |      | This button is used for accessing the Transfer To function\. The function may also be accessed from the Transaction Function group in the Function menu\.            |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/0c300b90-b95c-4ca8-a553-7d7646e319db.png) **Archiving**                   |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/df43f35b-d0a1-428b-9db0-9135ae5656a2.png) **DB Dictionary**               |      | This button is used for accessing the DB Dictionary function\. The function may also be accessed from the Maintenance group in the Function menu\.                   |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/400439ea-1c2f-4a67-b8c3-76e8999db760.png) **Calculation Constant**        |      | This button is *currently not used\.*                                                                                                                                |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/6bab9010-edd0-4e75-b10d-42f9dcfec314.png) **XML Generator**               |      | This button is used for accessing the XML Generator function\. The function may also be accessed from the Maintenance group in the Function menu\.                   |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/cf452b8b-beeb-4564-804e-bcc361df90b6.png) **Business Unit**               |      | This button is used for accessing the Business Unit Config function\. The function may also be accessed from the User Manage group in the Function menu\.            |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/e0bd87cc-48e5-4bb4-a119-5209cef61938.png) **User Manager**                |      | This button is used for accessing the User Manage function\. The function may also be accessed from the User Manage group in the Function menu\.                     |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/10f420f5-5cd3-432c-8ece-ff3a41a9a31a.png) **Import/Export Business Unit** |      | This button is used for accessing the Import/Export Business Unit function\. The function may also be accessed from the User Manage group in the Function menu\.     |
|                                                                                      |      |                                                                                                                                                                      |
| ![](images/e3d85972-309e-48ca-8a82-ea1b1b91e55b.png) **DataSource Manager**          |      | This function is used for accessing the Data Source Manage function\. The function may also be accessed from the User Manage group in the Function menu\.            |









Popup Menu

Inside a function or configuration window, options may be provided in the form of a popup menu\. This menu is displayed by right\-clicking on the relevant window section or on the relevant information\. 



| ![](images/753be66f-478f-4863-9493-1d11db84bfe9.png) |
| :--------------------------------------------------: |

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



|  Log on CE Utility as an Administrator or Operator user with rights to the XML Generator function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      | ![](images/67a16974-942e-4eab-a3b2-cfa67c656fd4.png) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| The CE Utility window is displayed\.<br><br>Run the XML Generator function from the Maintenance function group\.<br><br>Alternatively, click on the XML Generator button in the function toolbar\.                                                                                                                                                                                                                                                                                                                                                       |      | ![](images/9a92338d-03cc-4c62-99ca-66191c13cdef.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| The XML Generator function window is displayed\.<br><br>When there are newly defined or modified parameters, the Meta Data to XML window is also displayed\.  It lists these parameters for easy selection\.  In this case, the parameter can be selected from this window and the Apply button clicked\. Afterwards, proceed to Step 5\.<br><br>Alternatively, the Meta data or parameter can be manually selected from the main XML Generator window\.  In this case, click on the Close button of the Meta Data to XML window and proceed to Step 4\. |      | ![](images/26345db4-123f-4909-8c40-2b17d941a85c.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| Double\-click on the relevant parameter type from the XML Generator window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](images/3a8a1e87-863c-431f-ad4a-d98c505b3ad3.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| Depending on the selected parameter type, an XML configuration window may be displayed\. In other cases, the process directly proceeds to Step 6\.<br><br>If the configuration window is displayed, indicate the exact or any additional setting required to generate the relevant XML files\. When the specifications are defined click on the Save button                                                                                                                                                                                              |      | ![](images/ab00b942-4bb9-4fa2-8713-ff54624fe675.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| A message is displayed confirming if the XML files are to be generated on the system path\.                                                                                                                                                                                                                                                                                                                                                                                                                                                              |      | ![](images/5aff78a3-b058-45e2-bd16-6d0a698e1b45.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">The path of the XML files is defined through the GEN\_XML\_ROOTPATH Utility Workbench system parameter\. This system parameter is configured through the System Parameter function from the Parameter Manage function group\.</span>                                                                                                                                                                                           |      | ![](images/f18337cc-a23a-4a5d-8671-c24876c8ede3.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| To save the XML file on the relevant system path, click on the Yes button\.<br><br>To specify another path, click on the No button\. On the Save dialog box that is displayed, browse for the path and click on the Save button\.                                                                                                                                                                                                                                                                                                                        |      | ![](images/8df6a299-e9b4-4721-98d7-decb4af031a3.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| When the relevant XML files are generated, the system displays a confirmation message\.<br><br><br><br><u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">To hide the information on the paths of the generated XML files, click on the Hide button\.</span>                                                                                                                                                                                                                      |      | ![](images/ce2bfdef-dd7f-4021-aaad-157925be7ea6.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| <u><span style="color:#008080">**NOTE**</span></u><span style="color:#008080">:</span><br><br><span style="color:#008080">Check the indicated path\(s\) to see the generated XML files\.</span>                                                                                                                                                                                                                                                                                                                                                          |      | ![](images/af48fa63-0f44-4b92-9738-dff8fe6b2173.png) |











Building a Product

When building a product in the CE Utility, a few prerequisites are required to be met to make sure that modules or products are built in accordance with the bank's requirements\.  One step is the GAP analysis which involves an evaluation of transaction requirements, based on the process flow \(e\.g\., fields, clauses, forms, and interfaces\)\.  These are necessary for identifying the fields required for anticipating the required output\.  When the analysis has been completed, the project team can now begin the process of building a product for the bank's customers\.

The following are steps in building a product:



**Access the CE Utility**\.  To access the CE Utility for building parameters, an Operator user must be created by an Administrator user\.  This is set up through the User Manager function in the User Manage function group\.

**Set up the module and events**\.  This involves naming the module and the projected events that manage the transaction flow within the module\.  This is set up in the Module and Event function in CE Utility\.

**Set up the transaction tables\.** This involves creating the tables in the DB Dictionary function in CE Utility\.  There can be different types of tables but only three are mandatory for a CE module: master, ledger, and event\. 



![Tzone55](images/b76ad6b0-5267-48cc-b16b-b63b6641845a.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**It is possible to create tables directly into the database by running SQL scripts in the database\.  In this case, tables can be created before modules and events\.  It is recommended, however, to use the DB Dictionary for creating tables\.**</span>





**Add fields to the transaction table**\.  Fields must be added to a transaction table and field properties defined for the processing and storage of data\.  These can be done through the DB Dictionary function in CE Utility\.

**Set up the transaction functions**\.  This involves creating the functions that correspond to actual business transaction processes\.  This is done through Transaction Function in the Transaction Function group\.

**Set up the transaction parameters**\.  This involves designing the transaction screen, defining attribute and catalog settings, and attaching these parameters to the transaction function\.  These can be done through Transaction Function in CE Utility\.

**Create the product\.** The product is the actual functionality accessed and run by the end\-user\.  This process of creating a product involves setting up the product group, product, and product function, and defining product catalog settings\.

**Define authorization rules**\.  Authorization rules are set to further define or set limits for authorizing transactions\. 

**Calculation\.** This involves configuring the transaction JS files and defining calculation functions using available system methods\.  There are three JS files that have to be configured: the Module Base JS file, Event JS file, and Function JS file\.

**Define the settings for the transaction input\.** Certain functions may be added to aid in the input of data into the transaction\.  The CE Utility provides options for setting up field conversion rules, lookup buttons, customer reference numbers, clauses, dropdown lists, and data objects for this purpose\.

**Define the settings for the transaction output\.** Some business transactions involve output generation \(i\.e\., Forms\)\.  To make this option available, certain settings must be configured using the functions from the Transaction Function group in CE Utility\. 

**Define the security settings in the CE browser\.** The products and functions created are assigned to an end\-user through the browser\-side Security and System Maintenance functions\.



![Tzone55](images/a7c2e202-f5b0-43be-9fff-30461f09db5c.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**The browser\-side security and system maintenance functions of CE are often collectively called the Security Module\.**</span>





**Add the Inbox functionality\.** Another way of accessing a product or a transaction for further processing is through the Customer Inbox\.  This can be set up through the Inbox function in CE Utility\.



![Tzone55](images/de171ccf-645d-4806-a150-ee6428b12928.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**For more information on configuring different parameters in CE, refer to the**</span> <span style="color:#008080">***CE Utility Reference***</span> <span style="color:#008080">**manuals**</span><span style="color:#008080">***\.***</span>









Archiving Prerequisites

Archiving / BACKUP Database Settings

Data Source Settings

Log Settings

Archiving / Backup Database Settings

Transaction records are archived into a separate Backup Database, i\.e\., the archiving database\.  

This Backup Database must have the same table structure as the physical Transaction Database\.  When the table structures of the Transaction Database is changed, modify the corresponding table structures in the Backup Database by manually running the relevant SQL statements in this archiving database\.





![Tzone55](images/55a90b62-7cc3-4d66-9cdf-2dd3f3af4df3.jpeg)<span style="color:#008080">**NOTE:**</span> <span style="color:#008080">The Backup</span> <span style="color:#008080">Database</span> <span style="color:#008080">setting</span><span style="color:#008080">s</span> <span style="color:#008080">must be configured in the same application server \(WAS\)\.</span>





Data Source Settings

For the Archiving and Recovery functionality of the CE system, two data sources are required: CEB and CEX\.

The CEB data source refers to the Backup data source and, thus, points to the physical archiving database\. Used for storing archived data, this Backup Database has the same table structure as the Transaction Database\.

The CEX data source points to the physical Transaction Database, and is essentially the same as the CET data source\.

The settings for the CEB and CEX data sources are configured in both WebSphere and CE Utility\.







WebSphere Data Source Settings

The required WebSphere settings are as follows\.



| <span style="color:#BFBFBF">**Do the following \. \. \.**</span> |
| ---------------------------------------------------------------- |



| Define the JDBC provider:<br><br>Name: Oracle JDBC Driver \(XA\)<br><br>Implementation class name: oracle\.jdbc\.xa\.client\.OracleXADataSource<br><br>Class path: $\{ORACLE\_JDBC\_DRIVER\_PATH\}/ojdbc6\.jar<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">ojdbc6\.jar</span> <span style="color:#008080">file is the JDBC driver for Oracle</span> <span style="color:#008080">12c</span><span style="color:#008080">\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                            |      | ![](images/5057fadb-4f5f-43c7-b9ed-a2b41828eb19.png)                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: | :--------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                  |
| Define the CEB data source:<br><br>Name: CEB<br><br>JNDI Name: CEB                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](images/e72bdd16-c3d3-450d-8074-c52b258a462f.png)                                                             |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                  |
| This must point to the Backup Database \(e\.g\., CEBK\)\.<br><br>Assign CETRX for:<br><br>Authentication alias for XA recovery<br><br>Component\-managed authentication alias<br><br>Container\-managed authentication alias<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">CETRX user</span> <span style="color:#008080">created</span> <span style="color:#008080">in the Oracle Database is</span> <span style="color:#008080">the user that is to access the Backup D</span><span style="color:#008080">atabase\. If this is not the same as the transaction database user, the</span> <span style="color:#008080">CETRX</span> <span style="color:#008080">alias</span> <span style="color:#008080">must</span> <span style="color:#008080">be set in the Global Security tab, JAAS \- J2C Authentication Data page of the WebSphere Application Server Administrative Console\.</span>  |      | ![](images/d96eca3c-c05e-43b7-b4db-8bce7a5ef96a.png)<br><br>![](images/75a0fdc4-5e57-4ace-8a3d-5769b5a51d62.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                  |
| Define the CEX data source:<br><br>Name: CEX<br><br>JNDI Name: CEX                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](images/70d38d20-9e07-4bdb-896b-3ddf84ec189f.png)                                                             |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |                                                                                                                  |
| This must point to the Transaction Database \(e\.g\., CEDB\)\.<br><br>Assign CETRX for:<br><br>Authentication alias for XA recovery<br><br>Component\-managed authentication alias<br><br>Container\-managed authentication alias<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The CETRX user is the same as the</span> <span style="color:#008080">CETRX user that is used to access the transaction database</span><span style="color:#008080">\.</span><br><br><span style="color:#008080">The CEX data source points to the physical Transaction Database, and is essentially the same as the CET data source\.</span>                                                                                                                                                                                                                                                                                                         |      | ![](images/56e16dfd-4dd9-48ac-85ad-a14f1968f9d4.png)<br><br>![](images/e66bb9ce-eb59-41bd-8995-214e1f983350.png) |





CE Utility Data Source Settings

Log on the CE Utility as a Super Administrator user and configure the following data source settings\.



| <span style="color:#BFBFBF">**Do the following \. \. \.**</span> |
| ---------------------------------------------------------------- |



| Run the DataSource Manage function from the User Manage group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![](images/53dea757-7204-4d51-b81b-ff4142c28342.png) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | ---------------------------------------------------- |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| Check the settings in the Transaction Data Source Manager tab of the DataSource Manage function window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![](images/48c1cbf5-3be5-4eda-a7de-62fd3163a74d.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| Modify or create the CEX data source\.<br><br>This data source must point to the Transaction Database, and reference the CEX JNDI setting and CETRX user profile\.<br><br>Make sure to select Archiving as the database type\.                                                                                                                                                                                                                                                                                                                                                                           |      | ![](images/0cd3a460-ed61-45c4-84f7-7ad1162ba906.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| Modify or create the CEB data source\.<br><br>This data source must point to the Backup Database, and reference the CEB JNDI setting and CETRX user profile\. <br><br>Make sure to select Backup as the database type\.<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">CETRX is the CE Transaction Database user that is to access the Backup Database\.</span>                                                                                                                                                                                   |      | ![](images/bf65932e-3e12-4619-a234-f33de5e0e14f.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| <u><span style="color:#008080">**XML GENERATION:**</span></u><br><br><span style="color:#008080">Log on as an Administrator or Operator user and run the XML Generator function\.</span><br><br><span style="color:#008080">Generate the XML file for the Data Source Manage</span><span style="color:#008080">r</span> <span style="color:#008080">parameter\.</span>                                                                                                                                                                                                                                   |      | ![](images/5b5b9879-4fb3-4013-97d9-4a7f089df99e.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |                                                      |
| <span style="color:#008080">The updated XML files are generated</span> <span style="color:#008080">on</span> <span style="color:#008080">this path:</span><br><br><span style="color:#008080">\[Parameter Drive\]\</span><span style="color:#008080">C</span><span style="color:#008080">E\_SYS\SYST</span><br><br><span style="color:#008080">The updated</span> <span style="color:#008080">ee\_dsmgr\.xml</span> <span style="color:#008080">file contains</span> <span style="color:#008080">details</span> <span style="color:#008080">on the bank groups which data sources have been set\.</span> |      | ![](images/b2bf1a23-b3f7-494e-9aa5-9fb9cd934f9b.png) |



Log Settings

Configure the settings for the Archive logs through this file:

\[CE Parameter Folder\]\CE\_SYS\CE\_Log\_Config\.xml



<u><span style="color:#008080">**EXAMPLE:**</span></u>

<span style="color:#008080">Archive Log</span> <span style="color:#008080">configuration</span> <span style="color:#008080">settings:</span>



![tmp114.jpg](images/51b108f8-7d81-49cb-8829-ccb8dde84301.jpeg)





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



| Run the Component Manage function from the Parameter Manage function group\.                                                                                                                                                      |      | ![](images/73776422-540a-4496-9828-f016266912de.png) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                   |      |                                                      |
| Access the Control component type\.                                                                                                                                                                                               |      | ![](images/a870fc87-6ed2-4f3b-a735-609b11a29512.png) |
|                                                                                                                                                                                                                                   |      |                                                      |
| Check or add the Trx Manager Archive Control component:<br><br>Component Name: Trx Manager Archive<br><br>Component Description: Trx Manager Archive<br><br>Class Name: TrxManagerArchive<br><br>Business Type: Delete Master Mgr |      | ![](images/b1c95034-533d-4f90-a1de-32ae53ebbe2f.png) |





Archive Product Items

Specific Archive product items are required to associate a manual Archiving function to the relevant Archiving product\.

Add the following product items \- 

Archive

RestoreArchive

InquireArchive



\- to this file:

\[CE Utility Directory\]\ce\_params\Script\_XML\product\_item\_prar\.xml\.



| ![](images/94b11845-fffe-480c-acc2-919215002e40.png) |
| ---------------------------------------------------- |

Figure 4\.  Product Items for Archiving







Once these product Ids are defined in the XML file, add these in the Product Item function\.  Log on the CE Utility as an Operator user:



| Do the following \. \. \. |
| :------------------------ |



| Run the Product Item function from the Product Function group\.                                                                                                                                                                                               |      | ![](images/01bc3ce2-2ee4-4a71-9c13-46f9b4829b18.png) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                               |      |                                                      |
| Add the Archive item Id:<br><br>Item ID: Archive<br><br>Item Name: Archive<br><br>Item Desc: Archive<br><br>Is Group: No<br><br>Position: Transaction<br><br>Item Button: Archive<br><br>Type: Delete                                                         |      | ![](images/bbd2fe33-6426-4267-a8b1-2619ce930df6.png) |
|                                                                                                                                                                                                                                                               |      |                                                      |
| Add the RestoreArchive item Id:<br><br>   Item ID: RestoreArchive<br><br>   Item Name: RestoreArchive<br><br>   Item Desc: RestoreArchive<br><br>   Is Group: No<br><br>   Position: Transaction<br><br>   Item Button: RestoreArchive<br><br>   Type: Delete |      | ![](images/8e6ac314-c904-4494-a281-cab398ae0a37.png) |
|                                                                                                                                                                                                                                                               |      |                                                      |
| Add the InquireArchive item Id:<br><br>Item ID: InquireArchive<br><br>Item Name: InquireArchive<br><br>Item Desc: InquireArchive<br><br>Is Group: No<br><br>Position: Transaction<br><br>Item Button: InquireArchive<br><br>Type: Inquire                     |      | ![](images/59e2e5d5-aaa9-4d9d-8e47-35a83462b855.png) |



Error Codes

Log on the CE Utility as an Operator user and define the following error codes for Archiving processes\.



| Do the following \. \. \. |
| :------------------------ |



| Run the Error Handling function from the Maintenance function group\.                                                                                                      |      | ![](images/4b7ce2a1-b42c-4397-8003-7bce5a2b65c2.png) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                            |      |                                                      |
| In the Catalog tab of the Error Handling function window, access the System node\.                                                                                         |      | ![](images/e53651f0-744f-4b4c-ae3a-9de3f1ce7dad.png) |
|                                                                                                                                                                            |      |                                                      |
| Check or add Error Code 000464:<br><br>Error Code: 000464<br><br>Error Key: System<br><br>Error Level: Error<br><br>Error Messge: "Archive failure"                        |      | ![](images/0106d755-5d1b-4781-926c-d0bee0fe344c.png) |
|                                                                                                                                                                            |      |                                                      |
| Check or add Error Code 000465:<br><br>Error Code: 000465<br><br>Error Key: System<br><br>Error Level: Error<br><br>Error Messge: "Exception occur when restoring Archive" |      | ![](images/e8f14dd3-c092-46bb-8012-4ee51a3a4e6a.png) |





JSP and JS Settings

Modify the JSP and JS settings of the relevant transaction module to support the Archiving and Recovery functionality\.

Examples of such settings are provided in [Appendix:](<error reading>) \.



Archive Data Function

This function is used for archiving records\.  



![Tzone55](images/c9e78699-dc6c-4b30-bd55-a8d70bef1861.jpeg)<span style="color:#008080">NOTE:</span> 

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



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![](images/1b32e9cd-6881-451c-8017-1e78c4dc462b.png) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                      |
| Access the module and function group for which the Archive Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                            |      | ![](images/c86d6197-3133-43e6-9e3f-95dbc4daae5b.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                      |
| Create the Archive Data function and set its main program to Trx Manager Archive\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Archive Data</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Unmark the following flags:</span><br><br><span style="color:#008080">Check for Lock in Master</span><br><br><span style="color:#008080">Hold Master</span><br><br><span style="color:#008080">Need Lock</span><br><br><span style="color:#008080">Release</span> |      | ![](images/9c411e3f-97b3-4cad-97ee-e39348aa1b10.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                      |
| Define the relevant Attribute settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![](images/60fbcde3-8aad-46f8-b6b9-72d574305d7d.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                      |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      | ![](images/e2c4c1ea-7fc9-4d76-b239-84ef68bb6f70.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      |                                                      |
| <u><span style="color:#008080">**NOTE**</span></u><u><span style="color:#008080">**:**</span></u><br><br><span style="color:#008080">If this manual Archive function is to be used to archive a record that has been received via STP, the STP settings must also be configured through the STP function component\.</span><br><br><span style="color:#008080">For</span> <span style="color:#008080">details</span> <span style="color:#008080">on STP Archive functions, refer to:</span><br><br>Chapter Six: Archiving through STP                                                                  |      | ![](images/27018054-503f-4212-93d5-70bebb830a62.png) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](images/0582a690-829b-4970-b54b-36d384693e9d.png) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](images/0d76d4c1-2c20-4e1f-84c6-62e439851998.png) |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Select the Archive Data function \(e\.g\., IMLC Archive Data\) and assign these settings:<br><br>Item: Archive<br><br>Item Type: Delete                                                                                                                                                         |      | ![](images/b24831a0-84ed-437e-b91c-4d2261495170.png) |



Transaction Process



| EXAMPLE |
| :------ |



| IMLC Archive Data Function<br><br>Run the IMLC Archive Data function\.                                                                                                                                                                                                            |      | ![tmp118.jpg](images/422972d0-2255-423f-83ea-3917f8049215.jpeg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| Select one record and click on the Archive button\.<br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp119.jpg](images/79620b41-1c07-4726-9e24-3cd6bcaa124d.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| IMLC Inquire Archive Function<br><br>Run the IMLC Inquire Archive function\. <br><br>The catalog shows the archived record\.  Select this record and click on the InquireArchive button\.                                                                                         |      | ![tmp120.jpg](images/98bc881d-7069-4ecc-ab68-76d462f6a4a2.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| The documents and uploaded images for this record are listed for viewing \(through the corresponding View buttons\)\.                                                                                                                                                             |      | ![tmp121.jpg](images/94e2bfe8-e2ad-4de3-9c40-d14878c5a87f.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| Click on the View Historical button\.                                                                                                                                                                                                                                             |      | ![tmp122.jpg](images/fb4c49bd-3ba3-4f6f-ba5f-6267cab352da.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| The events of the transaction record are listed\.                                                                                                                                                                                                                                 |      | ![tmp123.jpg](images/8d5051ac-dce9-46b8-8414-ede4bd82219d.jpeg) |
|                                                                                                                                                                                                                                                                                   |      |                                                                 |
| Select an event to view the event details\.                                                                                                                                                                                                                                       |      | ![tmp124.jpg](images/70ca3602-1002-47d6-848b-023e21199809.jpeg) |





Restore Archived Data Function

This function is used to retrieve transactions from the Backup Database, and add these back to the master file\.

When the record to be restored already exists in the Transaction Database, the Restore process may not be performed on this record\.

When a record is restored, all related events are also restored in the corresponding tables\.





![Tzone55](images/bd363ac5-8a1e-4eb1-9e35-656d8ae1ae31.jpeg)<span style="color:#008080">NOTE:</span> 

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



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![](images/7e725478-c0f5-4812-b267-2722468c5408.png) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Access the module and function group for which the Restore Archived Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                               |      | ![](images/17757516-4ea3-4409-ae8f-cfea17b3c8e9.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Create the Restore Archived Data function and set its main program to Trx Manager Archive\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Restore Archive</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Unmark the following flags:</span><br><br><span style="color:#008080">Check for Lock in Master</span><br><br><span style="color:#008080">Hold Master</span><br><br><span style="color:#008080">Need Lock</span><br><br><span style="color:#008080">Release</span> |      | ![](images/0f95e448-fa0d-47a4-a546-1550261672ed.png) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![](images/e9d0868b-e196-44c5-abdf-702eaf7eb4ac.png) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](images/331ad129-c71a-457d-8687-6e61a8665614.png) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](images/d1a6b4f3-a928-4629-ab06-bf318b5a73be.png) |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Select the Restore Archived Data function \(e\.g\., IMLC Restore Archive\) and assign these settings:<br><br>Item: RestoreArchive<br><br>Item Type: Delete                                                                                                                                      |      | ![](images/0bf91139-62c4-43ff-bec0-8f12cace5b7b.png) |



Transaction Process






-----

<span style="color:red">**Table has a different set of cells in one/more rows. It can't be shown in Markdown**</span>

-----






Inquire Archived Data Function

The Inquire Archived Data function is used to inquire into records that are stored in the Archive file\.





![Tzone55](images/6b29fc59-8b39-40b3-8211-c7c42f57fe02.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**Unlike other**</span> <span style="color:#008080">**inquiry**</span> <span style="color:#008080">**functions, the Inquire Archived Data function retrieves**</span> <span style="color:#008080">**details**</span> <span style="color:#008080">**from the Backup Database \(i\.e\., CEB data source\) and not from the Transaction Database\.**</span>







Parameter Settings

Log on CE Utility as an Operator user and configure the following transaction function and product settings\.





Transaction Function Settings



| Do the following \. \. \. |
| :------------------------ |



| Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                     |      | ![](images/427b4942-6449-4071-864b-0760f55cd264.png) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Access the module and function group for which the Archive Data is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span> |      | ![](images/4887cb95-4b04-4e82-85af-4ddc82820320.png) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Create the Inquire Archived Data function and set its main program to Trx Manager Inq\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Inquire Archive</span>                                                                             |      | ![](images/44ea28ab-1741-42a8-9674-4ceae91548fd.png) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Attach the transaction JSP and template JSP files to this function\.                                                                                                                                                                                                                                               |      | ![](images/1e336a83-32fc-4280-a7f3-459bbd70bca9.png) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Define the relevant Attribute settings for this function\.                                                                                                                                                                                                                                                         |      | ![](images/61cc0f0d-64c7-40d4-936e-a307f0f1b63f.png) |
|                                                                                                                                                                                                                                                                                                                    |      |                                                      |
| Define the relevant Catalog settings for this function\.                                                                                                                                                                                                                                                           |      | ![](images/df7e30d6-12d8-498d-a29c-03af80d0257a.png) |









Product Settings



| Do the following \. \. \. |
| :------------------------ |



| Access the Product Function Setting function from the Product Function group\.                                                                                                                                                                                                                  |      | ![](images/98a8744e-bf9b-4295-ab9a-27c7e31f5bba.png) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :--------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Access the relevant product group and product from the Product Function tab\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Product Group: Import</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span> |      | ![](images/4e418c15-f912-442c-9163-6ad09d1513d6.png) |
|                                                                                                                                                                                                                                                                                                 |      |                                                      |
| Select the Inquire Archived Data function \(e\.g\., IMLC Inquire Archive\) and assign these settings:<br><br>Item: InquireArchive<br><br>Item Type: Inquire                                                                                                                                     |      | ![](images/651abd79-4a76-4acc-937c-f44b406ea59c.png) |



Transaction Process



| EXAMPLE |
| :------ |



| Through the IMLC Archive Data function, archive one record\.                                                                                         |      | ![tmp119.jpg](images/353839d2-9976-4062-878e-04ba7ebb8fa1.jpeg) |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-------------------------------------------------------------: |
|                                                                                                                                                      |      |                                                                 |
| Run the IMLC Inquire Archive function\. <br><br>The catalog shows the archived record\.  Select this record and click on the InquireArchive button\. |      | ![tmp120.jpg](images/c42f9f22-1c89-4ac3-9a0f-3b24e6b50b7b.jpeg) |
|                                                                                                                                                      |      |                                                                 |
| The documents and uploaded images for this record are listed for viewing \(through the corresponding View buttons\)\.                                |      | ![tmp121.jpg](images/a1d3bd47-781c-4ab6-acde-75eafa761d3c.jpeg) |
|                                                                                                                                                      |      |                                                                 |
| Click on the View Historical button\.                                                                                                                |      | ![tmp122.jpg](images/7bc8f825-c032-47a6-85b3-9178c00104f0.jpeg) |
|                                                                                                                                                      |      |                                                                 |
| The events of the transaction record are listed\.                                                                                                    |      | ![tmp123.jpg](images/09177d27-3de5-4bbc-9684-9c2ed8180249.jpeg) |
|                                                                                                                                                      |      |                                                                 |
| Select an event to view the event details\.                                                                                                          |      | ![tmp124.jpg](images/f3703e14-79bf-4988-a5a4-d2fdce219d19.jpeg) |





Auto Archive Mode

Overview

parameter SEttings

Transaction Process



Overview

With the Auto Archive mode \(or batch mode\), records from the relevant module that satisfy a defined set of criteria for the module are automatically archived\.  

The AutoArchiveData batch function is an example of an Auto Archive function\.





![Tzone55](images/9f805267-6cde-4392-b836-bb88c29c7f24.jpeg)<span style="color:#008080">NOTE:</span> <span style="color:#008080">**Each module has its own Archive conditions, which are set through the**</span> <span style="color:#008080">**Sub Task function**</span> <span style="color:#008080">**of the CE Utility\.**</span>  <span style="color:#008080">**Refer to the**</span> <span style="color:#008080">**succeeding**</span> **[Par](<error reading>)** <span style="color:#008080">**section for more**</span> <span style="color:#008080">**details**</span> <span style="color:#008080">**on setting the archive conditions for each module\.**</span>





 





Parameter Settings

One of the tasks under the AutoProcessTaskMgr batch manager, the AutoArchiveData batch function is used to automatically archive transaction records from a particular module that satisfy a defined set of criteria\.

The parameter settings for this batch function involve settings in the Sub Tasks, AP Server, Import/Export Business Unit, and Batch Manage functions\.  Log on the CE Utility as an Operator user and configure the following settings\.



| Do the following \. \. \. |
| :------------------------ |



| Sub Tasks<br><br>Run the Sub Tasks function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![CEv3_189.jpg](images/4c2d3e48-58ee-4ce4-8048-3c8314a840ef.jpeg)     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Access the Auto Process Manage subtask type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      | ![CEv3_190.jpg](images/6413bf24-050b-4acc-8a04-ba4c978c8349.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Configure the AutoArchiveData settings as required, and make sure to define the following:<br><br>Task Name, Task Description, Task Component: AutoArchiveData<br><br>Start Schedule Type and related settings<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The</span> <span style="color:#008080">Month, Week Day, Day,</span> <span style="color:#008080">and</span> <span style="color:#008080">Hour</span> <span style="color:#008080">fields are enabled based the Start Schedule Type field setting\. Define the values of these fields as well as the Minute component of the archive task schedule accordingly\. Refer to the</span> <span style="color:#008080">*CE Utility Referenc*</span><span style="color:#008080">*e*</span><span style="color:#008080">*:*</span> <span style="color:#008080">*Transaction Functions*</span> <span style="color:#008080">documentation</span> <span style="color:#008080">for more</span> <span style="color:#008080">details</span> <span style="color:#008080">on these settings\.</span><br><br><span style="color:#008080">Marking the Start Server flag allows a user to manually start the AutoArchiveData task\.</span><br><br><span style="color:#008080">The Time</span><span style="color:#008080">r</span> <span style="color:#008080">\(Hours\) field pertains to the duration within which the system archives the records that meet the criteria\.  If the records are not archived completely within this period, the system terminates the archive process\.</span>  |      | ![CEv3_191.jpg](images/0f105e7d-eba6-4540-86c3-205667493643.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| AP Server<br><br>Run the AP Server function from the Parameter Manage function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      | ![CEV30_Archive-02](images/83fdaba0-a4ce-401b-9d4e-76006cba495d.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Define or modify the AP Server settings: Name, Host Name, and IIOP Port\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEV30_Archive-03](images/4dac5afb-701a-4d9a-94ac-b2bd60ba4cd9.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Import/Export Business Unit<br><br>Run the Import/Export Business Unit function from the User Manager function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      | ![CEV30_Archive-04](images/348dbd4c-2616-4ee0-b036-75f5e74e4512.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| In the Import/Export Business Unit window, select the Application Server setting and click on the Import button\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      | ![CEV30_Archive-06](images/6f09be7d-fd1d-4dd0-8170-a03b6af92ef7.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Batch Manage<br><br>Run the Batch Manage function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_192.jpg](images/36ca4e9e-88ab-498e-accc-f447b9fd7ecc.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Create or modify the AutoProcessTaskMgr batch manager\. Select the correct AP Server Name setting\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![CEV30_Archive-08](images/02d2337d-d64a-4246-b21e-8a9356d1ab1f.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Add AutoArchiveData as a subtask of the AutoProcessTaskMgr batch manager\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |      | ![CEv3_193.jpg](images/29d72f13-15ca-4505-9be7-06ef10fb171c.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Sub Tasks<br><br>Run the Sub Tasks function from the Transaction Function group\.<br><br>Access the Archiving subtask type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |      | ![CEv3_194.jpg](images/31b4a79f-f540-4cac-9a8c-83d38d599003.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |
| Access the relevant module and define the following settings\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_196.jpg](images/a082c062-d6e1-4c01-b591-6b4e69b1f387.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      |                                                                       |



| Fields: Select PARENT\_MAIN\_REF <br><br>This reference number is used to identify the transaction and all its associated data \(e\.g\., images, documents\)\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_197.jpg](images/3f996cd5-217b-4c88-b120-d155643ccb63.jpeg)     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-------------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                       |
| In the text area, define the condition by which records from the module are archived\.<br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">The SQL keywords \- such as</span> <span style="color:#008080">SELECT</span> <span style="color:#008080">and</span> <span style="color:#008080">FROM</span> <span style="color:#008080">\- must be in uppercase\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |      | ![CEv3_198.jpg](images/b976eaf1-a458-41bb-a86f-731fa9b324e6.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                       |
| <u><span style="color:#008080">**XML GENERATION:**</span></u><br><br><span style="color:#008080">Generate the XML file for the</span> <span style="color:#008080">Archive</span> <span style="color:#008080">parameter\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![CEv3_199.jpg](images/6a9a506e-153c-4cdb-829a-705a8fc6f792.jpeg)     |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                       |
| <span style="color:#008080">Select</span> <span style="color:#008080">all</span> <span style="color:#008080">module</span><span style="color:#008080">s</span><span style="color:#008080">\.</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Selecting a</span><span style="color:#008080">ll modules</span> <span style="color:#008080">is recommended as the system</span> <span style="color:#008080">generates XML only for the selected modules and</span> <span style="color:#008080">deletes all previously generated XML for</span> <span style="color:#008080">the unselected</span> <span style="color:#008080">modules from the Archive folder</span> <span style="color:#008080">under the</span> <span style="color:#008080">CE\_SYS</span> <span style="color:#008080">directory</span><span style="color:#008080">\.</span> |      | ![CEV30_Archive-10](images/ff646735-8267-49da-9a04-c6376fc8ebc8.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |                                                                       |
| <span style="color:#008080">The following files are generated in</span> <span style="color:#008080">\[Parameter Drive\]\CE\_SYS\ARCHIVE:</span><br><br><span style="color:#008080">autoporcess\.xml</span><br><br><span style="color:#008080">module\_\[module short name\]\.xml</span><br><br><span style="color:#008080">multiPending\.xml</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEV30_Archive-11](images/678d9e00-b224-4402-b1df-48966a084881.jpeg) |









Transaction Process



| EXAMPLE: |
| :------- |



| Run the Batch Manager function and display the AutoProcessTaskMgr task manager\.<br><br>Start the AutoArchiveData subtask\.                                                                                                                                                                                                                                                                                                                               |      | ![tmp126.jpg](images/57153afc-54ca-42f8-b5dd-d670e12465ac.jpeg) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | :-------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                 |
| Execute this SQL to check which records meet the archiving filter condition\.                                                                                                                                                                                                                                                                                                                                                                             |      | ![tmp127.jpg](images/9eb426ae-2e21-454c-9797-d8bf010b4bd4.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                 |
| Three records are archived according to the archiving period and archiving condition specified in the parameters\.  \(These pertain to the Auto Process Manage and Archiving settings defined in the Sub Tasks function\.\)<br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp128.jpg](images/157e0014-316e-487c-aab1-c1e4f6375fec.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      |                                                                 |
| Run the IMLC Inquire Archive function\.<br><br>The three records, along with their associated data, can be accessed through this function\.                                                                                                                                                                                                                                                                                                               |      | ![tmp129.jpg](images/ffa9e605-1ff4-4ddb-a441-eab2c2e4c618.jpeg) |











Archiving through STP 

Overview

Parameter Settings

Transaction Process







Overview

When a record in the back\-office system is archived, the corresponding record in CE must also be archived\. 

The back\-office system sends the transaction's main reference number and other details to CE\.  CE, in turn, receives the data through Auto Process function and archives the relevant record through the STP Archive Data function\.  





![Tzone55](images/33ff0237-cc7b-44cd-9c5c-569fbce4832f.jpeg)<span style="color:#008080">NOTE:</span> 

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



| Extension Field<br><br>Run the DB Dictionary function from the Maintenance function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_208.jpg](images/2b83829c-a895-4b7e-9deb-98e6433dddd0.jpeg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :---------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Access the Reformat tab on the DB Dictionary function window\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_209.jpg](images/5db0a9c8-e01f-4cf0-8854-9c6a9cde2d06.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Add an extension field or tag which is to be used for storing module details sent from the back\-office system:<br><br>Name: Module<br><br>DB Type: VARCHAR<br><br>Length: 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      | ![CEv3_210.jpg](images/c69ea1fa-0604-4c4f-930f-1fa5dc1c438a.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| STP Mapping<br><br>Run the STP Mapping function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_212.jpg](images/cb8543d2-1d95-4d41-9f01-9689df698dc8.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Create the Archiving template\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Template ID and Template Description:</span> <span style="color:#008080">ARCHIVE</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEv3_213.jpg](images/d486d40a-fea7-4c9c-9972-f19a733e422b.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Add the following Receive tags, which pertain to field details of the transaction from the back\-office system:<br><br>Module, which pertains to the transaction module <br><br>CEMainRef, which pertains to the main reference number of the transaction<br><br>CustId, which refers to the Customer or Company Id                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |      | ![CEv3_214.jpg](images/15a1e378-ed24-4869-8313-1db43c77d39b.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Create an STP mapping rule and map the template tags to the relevant fields:<br><br>CEMainRef: C\_MAIN\_REF<br><br>CustId: C\_UNIT\_CODE <br><br>Module tag: C\_MODULE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      | ![CEv3_215.jpg](images/a514cc74-a670-474b-a3a0-8ffc8e97e495.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| STP Setting<br><br>Run the STP Setting function from the System Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      | ![CEv3_216.jpg](images/a772e389-4a6a-4741-97d4-53a515ba310d.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Access the Assign Function tab for the Incoming Message STP type\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |      | ![CEv3_218.jpg](images/e9f4e0dd-ca05-4a77-94a2-90ad03ea8018.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Select the relevant message type \(i\.e\., the defined STP template\)\.<br><br>Assign the function that is to process the STP message through the stp\.setFunc method\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Transaction function: IMLC Archive Data</span><br><br><span style="color:#008080">Product: Import Letters of Credit</span><br><br><span style="color:#008080">Code:</span><br><br><span style="color:#008080">stp\.setFunc\("IMLC Archive Data", "Import Letters of Credit"\)</span>                                                                                                                                                                                                                                                                |      | ![CEv3_219.jpg](images/991dc6e0-8457-44ed-bbae-760fda4c0980.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Transaction Function<br><br>Run Transaction Function from the Transaction Function group\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |      | ![CEv3_168.jpg](images/1ea37b8e-a1d0-4612-bdf0-646c996434e4.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Access the module and function group for which the Archive Data function is to be created\.<br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Module: Import Letters of Credit</span><br><br><span style="color:#008080">Function Group: System Maintenance\.</span>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      | ![CEv3_169.jpg](images/0c408f35-90c0-4127-956b-d04c8efda0eb.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Access or create the Archive Data function, which is used for archiving the received STP message\.<br><br>For the required parameter settings, refer to Chapter Four > Archive Data Function > Parameter Settings\. <br><br><br><br><u><span style="color:#008080">**EXAMPLE:**</span></u><br><br><span style="color:#008080">Function: IMLC Archive Data</span><br><br><br><br><u><span style="color:#008080">**NOTE:**</span></u><br><br><span style="color:#008080">Only one function is used for both STP archiving and</span> <span style="color:#008080">manual archiving</span> <span style="color:#008080">processes: the</span> <span style="color:#008080">IMLC Archive Data</span> <span style="color:#008080">function, which</span> <span style="color:#008080">utilizes the Trx Manager Archive main program\.</span>  |      | ![CEv3_170.jpg](images/f5a99efb-af5e-4d1c-9337-6ca05d3e0e48.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| Define the STP settings for this function through the STP function component\.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |      | ![CEv3_173.jpg](images/c2b7c1bb-926d-4cae-b54f-d13d1e613b84.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |      |                                                                   |
| <u><span style="color:#008080">**EXAMPLE**</span></u>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![CEv3_174.jpg](images/46686e3a-b8b3-4692-bcb0-7fd45c21aca1.jpeg) |







Transaction Process



| EXAMPLE: |
| :------- |



| Send an STP message to CE\.                                                                                                                                                                                                                                                                                                                                                                                                                |      | ![tmp130.jpg](images/f3c30d56-eddd-455b-bae0-f49b62cf3538.jpeg) |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | :-------------------------------------------------------------: |
|                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                                 |
| Run the Batch Manager function and display the Message Broker task manager\.  Make sure that the InGapiForm subtask has been started\.<br><br>Check the STP Log: The STP message is received successfully\. <br><br>Check the Archive Log: All transaction event records \- and related data including images, documents, mails, GAPI, etc\. \- are archived into the Backup Database and deleted from the original Transaction Database\. |      | ![tmp131.jpg](images/76439f6f-4abc-46a8-b926-5873b0b863b5.jpeg) |
|                                                                                                                                                                                                                                                                                                                                                                                                                                            |      |                                                                 |
| Run the IMLC Inquire Archive function\.<br><br>The record, along with its associated data, can be accessed through this function\.                                                                                                                                                                                                                                                                                                         |      | ![tmp132.jpg](images/35fb8688-d005-49c3-9268-677578ff2174.jpeg) |















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


