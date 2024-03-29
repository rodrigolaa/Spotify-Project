# Spotify Project 
This project aims to create <b>Looker Studio Dashboard</b> with the top 50 tracks in the world. 
The data was retrived using a <b>Python</b> script that consumers the <b>Spotify API</b> and uses a <b>Lambda Function</b> to register the dta in a <b>Google Sheets</b>.

#### [Dashboard](https://datastudio.google.com/u/0/reporting/6ed6acc6-36f4-4366-a348-a297ba9c4e52/page/X8w4C).

What I have learnend?
 - How to create a google api.
 - How to create a spotfy api.
 - How to develop a python script to retrive API information and parse through JSON object.
 - How to deploy ZIP file in AWS Lambda Function with AWS CLI.
 - How to Set a EventBridge cron job in AWS Lambda Function to run every day.
 - How to ccreate a free, online and analytical dashboard in Looker Studio.

<img src="https://user-images.githubusercontent.com/50839107/196177479-c23fc2df-3e65-40d1-9fc2-b3ed9af138e6.png" width="700" height="250">


### 1) Get Spotify Credentials in [here](https://developer.spotify.com/dashboard/applications)

     Need To create an App, put a name and description for it, and you are good to go!

<img src="https://user-images.githubusercontent.com/50839107/196182699-468fc75c-483b-4557-9d95-11a9ced27026.png" width="700" height="250">


### 2) Get Google Sheets API - [Google Cloud](https://console.cloud.google.com/welcome)

     - First you need to create an account in Google Cloud
     - then, Create a Project
     - Create an Google Sheets API
     - Share the google sheets with the email generated with the Google Sheets API.
     - Save the credetials json file in the folder of the project.
     
     
For more details in how to configure the <b>Google API</b>  watch this video: [tutorial](https://www.youtube.com/watch?v=ddf5Z0aQPzY&t=292s)
     
     
![image](https://user-images.githubusercontent.com/50839107/196178326-f698ad02-266f-42ae-9b9c-97c42256c928.png)


### 3) Create Python Deployment Package (.zip) with all packages and code.

### 4) Upload the .ZIP file in a AWS Lambda Function with AWS CLI.

### 5) Set a Cron job with EventBridge alarm every day.

##### For more details, follow this [Tutorial](https://www.youtube.com/watch?v=OLXEekDzpHQ&t=12s)

![image](https://user-images.githubusercontent.com/50839107/196178492-751e3662-af7a-4579-bca2-edeacc4f7202.png)

#### Thanks!

