# AppRouter

The Purpose of this APP is to enable reading data from an Onpremise SAP System and expose the data to Cloud foundry environment .
Mentioned below are detailed steps for the Odata exposure from Onpremise system and the app is the last step in the below mentioned steps:

Steps for exposing data via OData to Cloud Foundry :

•	On Premise System  ( CDS View for exposing table data with OData service enabled ) 
•	Enable SAP Gateway Services in the backend to expose data as an OData service
•	In Cloud connector  
-	Create a connection to the Cloud Foundry Instance  
-	Map Actual server of the backend to a virtual host 
•	Create App in CF to pull data via cloud connector using the virtual host 
-	Create APP Using no authentication or Basic Authentication( Python) 


More details regarding the process can be found on the below Blog post :
