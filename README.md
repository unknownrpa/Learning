# Learning

Welcome to Primo RPA Learning!

Here, you will find project examples that showcase the functionality of Studio elements. These examples will help you understand how to use each element in your workflow.

All projects can be downloaded as a single archive. To do so, click in the top-right corner **Code > Download ZIP**:

![](<.gitbook/assets/how-download.png>)

It is recommended to download the materials as an archive rather than as separate processes because some projects may include additional resources (Excel files, test applications, etc.) that are essential for certain workflows to function properly.

## RPA Projects (PRO Mode)
These projects are developed in PRO mode within the Studio and utilize the **Sequence process** type.

* **StudioActivities** - An RPA project with a set of basic elements for automating various tasks. It includes components for working with FTP, Google Sheets, networks, Optical Character Recognition (OCR), PDFs, SAP systems, and more. Additionally, it provides elements for interacting with Microsoft Office applications, databases, browsers, as well as tools for managing data, charts, dialogs, and much more. 

* **ActiveDirectoryExamples** - A project designed to teach how to work with the Primo.ActiveDirectory package. It demonstrates the process of connecting to an Active Directory server and performing various actions, such as searching for objects, retrieving user attributes, and adding or removing users from a group. The project is intended to be executed on a machine that is on the same network as the Active Directory server.
  
* **ExcelGetInfo** - This project is designed for processing data in Excel files, with the primary task being the extraction of necessary information from files in this format.
During the process, you will learn how to use various tools such as range search, column and cell reading, as well as working with dates and regular expressions. An example Excel file, Schedule, is attached to the project for practice purposes.

* **WorkWithExcelExample** - This project demonstrates interaction with Excel files, including the use of core Primo Studio elements.
The project implements reading an Excel file via Interop using OnlyCode and a connected Interop dependency, as well as reading the file via OleDB with OnlyCode and the associated dependency. Additionally, it includes interaction with Excel using ODBC queries.
A detailed description of the process can be found in the document "Process Description - WorkWithExcelExample.docx", attached to the project.

* **OCRSnils** - This is a demo robot designed for the automatic recognition of SNILS numbers using OCR (Optical Character Recognition) components.
Using OCR technology, the robot can scan and analyze textual information in documents, extract, and recognize SNILS numbers. This automation accelerates and simplifies the processing of documents related to SNILS.
Examples of such documents can be found in the SNILS folder.


### RPA Projects (Citizen Mode)

The **Citizen** folder contains RPA projects developed in the Studio's Citizen mode, including:
* **AddNewClientsToCRM (Adding New Clients to the CRM)** - demonstrates the creation of an automated process for adding new data to the CRM.
* **SaveAttachOutlook (Save an Attachment from Outlook)** - the project includes a configuration that automatically saves attachments from emails received via Outlook. This can be useful for processing and storing important files received by email, helping to prevent data or document loss.
* **SaveExtractFromEGRUL (Save and Extract Data from the Unified State Register of Legal Entities (USRLE))** - the project is focused on extracting and saving data from the Unified State Register of Legal Entities (USRLE). It is used for analyzing company data, searching for information about specific organizations, and more. This project will help you learn methods for automated data collection from public sources, which can be valuable for analytical work.

### Project for Working with Pure Code

The **LearningPureCode** folder contains an RPA project where the **Pure Code** process type was selected for automation scenarios. 

The project contains three main subfolders: C, JS, and Python. These correspond to the programming language selected when creating the Pure Code process. The scenarios include operations with common Studio elements:
* Creating a table in Excel.
* Reading data from an Excel cell.
* Reading formulas from an Excel cell.
* Inserting a chart into Excel.
* Synchronizing folders in Outlook.
* Executing a VB script.

### Orchestrator's API 

**UploadProjectWithOrchApi** - This is a guide on adding a ready-made RPA project to the Orchestrator using the API. 
A detailed description of the API can be found in Swagger. To access Swagger, refer to the document "Guide to Opening Swagger", which is included in the Orchestrator package.

We wish you successful learning!
