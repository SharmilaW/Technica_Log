
Setting Up ArcGIS Server On GCP
Wednesday , March 06, 2024 

Start time 20:15pm 

Stop time 21:45pm 

Total Time 1:30  

 

Google credit was claimed and email address was provide to Shawn so that there was sufficient credit to start this process. 

Log into the google account which has been granted access by Shawn. 

To confirm if you have access check for Shawn's ArcGIS Server( If you do not see this you do not have access) 

Go to Google Cloud >Console> Project list>New Project 

Create My First Project( If it does not already exist during credit application)  

Since this is individual project location can be left as default ( No organization) 

![GVM](../images/GetImage.png)


Run a GCP Virtual Machine to test ArcGIS Server 

With your project (My First Project Geom99) Selected  

Compute Engine >VM instances> Create Instances 



Name VM ( needs to be arcgisserver-geom99 for academic purpose) but can be anything. 

Leave the region and zone as default which means the VM on a server in Iowa USA is being created. 

For Machine Configuration we will leave as default ( E2 which has 2vCPU and 4GB memory) which will be enough for our case. 

*** Depending on which Machine you select you will be charged so make sure you pay attention while choosing this.*** 

***In a business or production environment use Esri’s requirements (8gb RAM)*** 

We can choose different images to start (Mostly Linux based are free but we are using Microsoft Windows Server which is not free. 

 

We are using image provided by Shawn ( Stored in his account)  

Boot Disk> Change>CUSTOMIMAGES> Change> ALL> Select Shawn's ArcGIS Server(** Need to have been granted access) 
