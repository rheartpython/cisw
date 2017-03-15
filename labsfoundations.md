---
layout: page
title: Labs for Foundations
permalink: /labsfoundations/
---


Foundations Lab Content
---

**_CISW - Foundations Section 1:  Process and Platform, Environment Configuration_**

### Account Activation Cloud Discussion

1. Activate your Azure Subscription (either existing, trial or if you have an Azure pass - setup [here](#azure-pass))
  1. Open the Azure Portal at https://portal.azure.com
  * Create one empty Resource Group
* Explain a situation where data was used in a new and unexpected way in a business or an organization
* List three advantages to using a cloud or hybrid architecture
* List three objections to hosting an application in the cloud, and three responses to those objections


Set up the Data Science Virtual Machine

1. Log in to the Azure Portal
* Deploy one Windows Data Science Virtual Machine (DSVM) – note your admin name and password
  * Need help? Check here – except make sure you pick the Windows Data Science Machine! https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-provision-vm 
* Start the DVSM
* Connect to the DSVM and begin updating the Power BI, Visual Studio, and Windows environments
  * Need help? Check here: https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-connect-logon/  


Setting up the Storage Account and additional tools

1. Create a Storage Account in the region closest to the class location – note the name and access keys
* Connect to the Azure Data Catalog as described in the classroom login information
* Connect to http://studio.azureml.net  and create a free account for the class


**_CISW - Foundations Section 2:  Data Discovery and Ingestion_**

Adding and searching data on the Azure Data Catalog

1. Search for one on-line table involving your business scenario
* Connect to the Azure Data Catalog
* Add a Data Source as an HTTP site
* Add metadata to the information
* Save and view in Portal
* Search for your data element based on name or tag you added
* Add more tags
* Add yourself as an expert
* Search for your name as an expert

Copy and view data on your storage account using AZCOPY

1. Open the Azure Portal, locate your Storage Account (or create one if you have not), and a Container (or create one if you have not).   * Note the name of the SA and the Container, and your storage key.
* From your DVSM, or if you installed the Azure PowerShell tools locally, open a command prompt. 
  * If you do not have the AZCOPY command, download and install it here: http://aka.ms/downloadazcopy  
* Navigate to this page: https://azure.microsoft.com/en-us/documentation/articles/storage-use-azcopy/  
* Locate the section marked **“Blob: Upload - Upload single file”** and follow the instructions to load one file to your storage account, using your Storage Account and storage keys. 
* Next, locate the section on the web page with instructions marked **“Blob: Download - Download single blob”**. Follow the instructions there to copy your file to a new folder on your local computer. 


Exploring your data

1. Using the building.csv and HVAC.csv files in your \Resources folder, use R, Excel, Azure ML or any other exploration tools you’ve seen in the class to explore the shape, size, layout, distribution and other characteristics you can find in the data. 
* Document that in any format and be ready to discuss. 


**_CISW - Foundations Section 3:  Data Preparation_**

Create the ADF, Load your Source Data

1. Open the ADF Student Workbook file from your \Resources folder
* Follow the steps for Lab 1
* The follow the steps for Lab 2
  * Note – There’s a useful JSON prettifier here: http://www.jsoneditoronline.org/
  
Create the Linked Services

1. Open the ADF Student Workbook file from your \Resources folder
* Follow the steps for Lab 3

Create Datasets

1. Open the ADF Student Workbook file from your \Resources folder
* Follow the steps for Lab 4


Create Pipeline(s)

1. Open the ADF Student Workbook file from your \Resources folder
* Follow the steps for Lab 5

Monitor Pipeline(s)

1. Open the ADF Student Workbook file from your \Resources folder
* Follow the steps for Lab 6

**_CISW - Foundations Section 4:  Modeling for Machine Learning and Data Mining_**


Create and Run an Experiment in Azure ML

1. Open the AML Student Workbook from your \Resources folder
* Follow the instructions you find there

**_CISW - Foundations Section 5:  Evaluating the Model_**

Connecting to an Azure SQL Database

1. Optional: On your DVSM, you can connect to Azure SQL DB after you open the firewall. 
  1. Read this for creating a database server and database: https://azure.microsoft.com/en-us/documentation/articles/sql-database-get-started/  
  * In the portal, find and record your connection strings: http://www.connectionstrings.com/sql-azure/  
  * Read this to connect and browse to a database: https://msdn.microsoft.com/en-us/l

**_CISW - Foundations Section 6:  Deployment_**

Analyzing data in Power BI

1. Option 1: First-time, comprehensive example: https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-getting-started/  
* Option 2: EMEA soccer data example : http://tinyurl.com/buckwoodypbi1
* Option 3: US retirement example: http://tinyurl.com/buckwoodypbi2
* Option 4: Open Power BI or Excel, and use this data source:  http://services.odata.org/V4/Northwind/Northwind.svc/
  1. Define Relationships
  * Change the data types to be appropriate for location, summation, etc.
  * Create linked graphics based on those relationships and data elements

**_CISW - Foundations Section 7:  Workshop Recap_**

Business Case Applications




Select one of the following scenarios. Create a Business Case, a Solution Diagram, and a description of why you chose each technology in your solution and how the data flow path will work. Be as detailed as you can. You can submit three documents or including them all in one – Word, PDF, PowerPoint or Visio are all acceptable tools. 

1. Using the Contoso Medical Scenario, find the Marketing Partners bullet. How could you use the CIS process and platform to assist in determining optimal promotions? https://msdn.microsoft.com/en-us/library/ff650330.aspx  
* Contoso auto repairs wants to be able to predict the flow of repairs through their shops nation-wide, to properly staff, equip, set pricing and inventory for their operations. Which datasets do you think they need to collect to have this kind of predictive model? How would you go about documenting and ingesting this data? https://msdn.microsoft.com/en-us/library/ee861194.aspx  
* Contoso University wants to predict which students they should accept from high-schools around the country that will complete their degrees, and offer the best scores to the college. What processes can they use to determine these students, and which CIS platform elements could they use to create a yearly report for the Board of Admissions to give the most numerically accurate number? Describe your solution. 



**_Addendum_**

Azure Pass

**Optional.  Setup of the Azure Pass - Redeeming Pass and Activating Subscription**

Please find the details of the Azure Pass codes and instructions on how to access given below if this was an option provided by your instructor.

1.	Please use the passcode assigned to your name given after registration. Each passcode has a specific value and is valid for a 30 days from the date of redeeming it.
2.	Each student will need a Microsoft Account to redeem the Azure Pass code.
4.	Follow the instructions on how to redeem your pass code and how to activate your subscription using the tutorial given under this link https://www.microsoftazurepass.com/howto.  You will check that it worked by visiting the accounts page at  https://account.windowsazure.com/Subscriptions and seeing that "Azure Pass" is a subscription.
5.	Also, please make sure when using this subscription you are able to login to the Azure Portal at https://portal.azure.com and provision services.

IMPORTANT NOTE: Please **switch off** any Azure services that you used to run the hands-on-labs to make sure you save your remaining credit on the subscription for further use.

If I go to https://account.windowsazure.com and click on ACCOUNT CENTER, I see:

![my subscriptions]({{site.baseurl}}/images/azure/azure_pass5.PNG)

And if I check my "Azure Pass" subscription:

![my azure pass credits]({{site.baseurl }}/images/azure/azure_pass6.PNG)

This should match the amount of credit given to me and will be available for 30 days.

