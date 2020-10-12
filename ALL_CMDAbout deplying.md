<b>High-level Overview.</b>
----------------------------------------------------------------------------------------------------------------------------

1) Create a Project folder.
2) Create org env on the other side.                              <b>(Create org and Authorization)</b>
3) Authorize from client to server-side. (username, password, security token, session id)
                                       
-----------------------------------------------------------------------------------------------------------------------------

1) Create Content on one side.          (extension,config,env)    <b>(create content and Data Transfer)</b>
2) Push that content to another side.    
3) Deploy on the other side.            ( parsing ) 
-----------------------------------------------------------------------------------------------------------------------------
Salesforce and vs code configuration 
Note: Sfdx commands ( To List down all command) 

To create a project :
Ctrl + shift + p => create a project

To Authorize a org:
Ctrl + shift + p => authorize an org

To create content:
Ctrl+ shift + p => create lightning web component/ apex class/ component

Create a default seach org :
Ctrl + shift + p => default search org 
Push the code :
Sfdx force:source: push

Convert the code into meta data and deploy the meta code:

sfdx force:source: convert

sfdx force:mdapi:deploy -d metadataPackage_1581526248743 -u cosec@gmail.com -w 5 <br/>

                Folder Name  package name                     User Name

For Pulling any changes from other systems to one side:
Sfdx force:source:pull

-----------------------------------------------------------------------------------------------------------------------


