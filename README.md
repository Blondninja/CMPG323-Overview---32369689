# CMPG323-Overview---32369689

I have created 1 repository for this project in this Repo we have split it into 5 different branches for each specific individual project for eg. Project 2 will contain all the neccessary files for that project, we will then Push all the branches into the main branch where all the projects can be found.

Below is a Text diagram explaining the project and repo context and how they intergrate.

CMPG323-Overview Repo--->Main Branch--->Project 1--->Project 2--->Project 3--->Project 4--->Project 5
Above in the text diagram we have shown you that from the Repo we have branched 5 different projects from the main branch from the same repository. They are intergrated in such a way that Project 1 will not have an influence on other branches for example. Work that was done in project 1 will not affect project 2-5 and vice versa the only affect the branches will have is on the main branch when it is pushed or pulled.

explaining the branching strategy to be used within each project:

All projects are branched from 1 repository meaning that Project 1/Branch will not have an influence on other branches for example. Work that was done in project 1 will not affect project 2-5 and vice versa the only affect the branches will have is on the main branch when it is pushed or pulled. The branches are specifically set up in a way so that each project can be individually worked on, unless if they specify that we have to create an new repository for each project therefore we follow the criteria.

explain the use of a .gitignore file

gitnore is a file that tells the GIT to ignore a  project , because they are certain parts  in the project that you dont want it to be publish to your repository it could be credential files that you dont want them to be access by others  its not secure.
.gitignore tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as compilation products, temporary files IDEs create, etc.

student project structure:

project 1 is an agile and scrum where you have to develop an repository and connect the branches to the main repository . in this semester we have 5 projects that needs to be done throughout the semester, where specific dates are given for the projects. 5 repositories will be created for individual submission so that the projects may not mix with each other and the content stays in the specific repository
bring development issues and pull request
create a kanban project


purpose of the project:

you will create a CRUD RESTful API that will connect to a database storing
IoT device data. The API should contain at least one get, post, patch and delete method per
resource – aligning to the project's requirements. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database. 

The project is being scafold (dotnet ef) and therefore the models were being updated , the model have three categories namely category.cs , device.cs and zone.cs .
therefore one its being scafold the controllers is being added following up.

the controllers consist of Device , category ,zone and each of the controllers can output an GET METHOD, PUT METHOD , DELETE METHOD, POST METHODS. so that it can be hosted on the azure and output and thr swagger results.

we have used the gitignored so that the appsetting should not be accesed by the github, i have applied the authentification on the API and refrained the credentials from storing in the code 

the Api  and database is hosted on the azure and its has been granted access .

i have pushed the assignment on the github in case if i loose any data i can retrieve it from the github for backend purpose , and i have publish the project to the Azure and its publish successfully.

i have added 5 endpoints and made sure they are under owner 


REFERENCE LIST:
•	Tutorial: Create a web API with ASP.NET Core | Microsoft Docs 
•	Create a web API with ASP.NET Core controllers - Learn | Microsoft Docs 
•	ASP.NET Core web API documentation with Swagger / OpenAPI | Microsoft Docs 
•	Create microservices with .NET and ASP.NET Core - Learn | Microsoft Docs
•	Entity Framework Core 3.1 - Getting Started
•	Join two entities in .NET Core, using lambda and Entity Framework Core 
•	Publish an ASP.NET Core web API to Azure API Management with Visual Studio | Microsoft Docs
  

![image](https://user-images.githubusercontent.com/110628936/189643938-d00a78e2-4d4f-4c24-b26f-e1896367ba65.png)

![image](https://user-images.githubusercontent.com/110628936/189644320-c418c8cb-c04f-49b7-814a-c628f451a4a3.png)




explain the  storage of credentials and sensitive information:

 you can use the git store to store your passwords
 you can use the git store from the data being leaked
 delete confidential data that you no longer need which can create sensitive issue 
 restrict confidential data in workplace so that it may not go into a wrong hand and result in loss
 
 project 4
 
 
 Overview
Testing is a crucial part of any solution and can be done from many different perspectives; the
internal development team testing, business user acceptance testing (UAT), etc. There are also
many different types of testing that can be conducted on a solution and user acceptance testing
is usually done very manually. UAT is often included in most development lifecycles as a crucial
step that acts as the ‘go/no-go’ decision maker. UAT is focused on ensuring that the input entered
into the solution generates the expected output. If the solution does not generate the desired
output, the solution needs to be amended and retested as the solution would generally not be
published to production unless it passes all tests in UAT.
Robotic Process Automation (RPA) refers to the use of technology to mimic human tasks in the
same way that a person would execute a process. This usually refers to, what we would call,
‘front-end’ or UI (User Interface) automation. RPA is often used to automate time-consuming and
highly repetitive tasks to allow people the availed capacity to work on more intuitive tasks.
Let’s take the web application that you worked on in Project 3 – before the solution can be
deployed into production, it would need to go through UAT where a team of ‘testers’ would have
a test dataset containing input data and desired output data. The testers would then insert each
record of input data into each field of the web application and test that the desired output is
generated. In this case, the desired output would be a new record being displayed on the web
application once the item has been added. This would resort in a highly repetitive process which
can and should (in this case) be automated using RPA.


NOTE* All the creates for categories, zones , and device is working perfect
    * the delete,update ,create and insert are having correct structure following right steps but not running 100%

This repository contains  automation scripts for Project 4 of CMPG 323 created in UIPath Studio Community, the script test Basic CRUD activities on the Connected Office Web app

REQUIREMENT:

Before running this project please ensure that you have the following software installed on your computer:

UIPath Studio (Community) Minimum version 2022.10.2 (Recommended)
Microsoft Excel
Microsoft Edge
.Net SDK Version 6.0 (Recommended)
Installation and usage
Clone the Git repository into a local folder
Open "ConnectedOffice Webapp User Acceptance Testing" project in UIPath Studio

The Structure of the test suite is broken up as follows:

Delete - where you delete the selected item permanently and will never be recovered back.
Insert- is when you add an category to the office 
update - is when you change data from something to something eg. from maths to science 

NB: each of the test is done on each of the categories, device, and zones 

Category

*DeleteCategories
*InsertCategories
*UpdateCategories
*Main.xaml

Devices

*DeleteDevices
*InsertDevice
*UpdateDevices
*Main.xaml

Zones

*DeleteZones
*InsertZones
*UpdateZones
*Main.xaml

PROCEDURE:

NB: when you run the uipath studio , it will open the connected office , please always logout when you want to do the testing, and they might be errors which i couldnt solve , however the steps are there which i have provided but still not 100%

Click on the test that you would like to run and click the run button in UiPath Studio , when its displayed please press logout and then the automation will take place smoothly.
Once the test is successfully You will return to UiPath Studio where you can run another test

![Screenshot 2022-10-27 144617](https://user-images.githubusercontent.com/110628936/198290920-fd95fd31-0b98-48a0-94a2-7487d51685db.png)












