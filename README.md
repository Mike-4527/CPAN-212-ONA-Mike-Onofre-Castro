
About the Application:
The instructions to set up an Incidents application was to create specific folders and files, which is both backend and frontend, and inside the backend folder, there are routes, store, and utils. There are incidents.routes as a JavaScript file of the routes folder. There are incidents.store of the store folder. And inside the utils folder, there are three JavaScript files, which are config, csv, and validate. Inside the src folder that was created, an app JavaScript file was created and it is the most important file in the application to function when it runs. And there are also package and package-lock JSON files, which hold the data and the dependencies but the important file is the package JSON file, which consists of the package version, start file to run the application, and dependencies. And the last file of the backend folder is a server JavaScript file, which initiates the application at launch. In the frontend folder, there are a couple of folders in there, but there are two important folders, which are pages and incidents, but consists of different files needed to allow users to create, read, update, and delete incidents/files. These are the folders and files to set up an application. 

The API endpoint list are:

GET (Retrieve)
POST (Create)
PATCH (Update)
DELETE 
BULK (Upload Document)


The CSV format was created to allow users to upload the incidents on a list of incidents that the functionality of a bulk upload was implemented on both JavaScript files, which are bulk-upload and csv. The bulk-upload JavaScript was created using React to create bulk-upload functionality and creates a functionality to allow users to select a CSV file and upload it. The csv JavaScript file is responsible to parse the csv file to make sure the CSV file is readable if an upload has been successful. 
