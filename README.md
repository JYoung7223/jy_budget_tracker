
# JY Budget Tracker
[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
## Description
This Project uses Express, MongoDB with Mongoose, hosted with Heroku, using browser IndexedDB; to provide a simple budget tracker.  User may enter transactions and view some basic reporting on their transactions.  If offline the transactions will store in IndexedDB until online when it will sync with Mongo Atlas DB
## Table of Contents
* [`Project`](#)
* [`Description`](#Description)
* [`Table of Contents`](#Table-of-Contents)
* [`1nstallation Steps`](#Installation-Steps)
* [`Usage Information`](#Usage-Information)
* [`Testing`](#Testing)
* [`License`](#License)
* [`Contributing`](#Contributing)
* [`Questions`](#Questions)
* [`Sample`](#Sample)
## Installation Steps
To install this project, do the following:
> 1. To Install on "localhost", clone repository to local workspace.
> 2. Open terminal and run "mongod" to ensure the MongoDB service is running.
> 3. In a seperate terminal, in project base directory, run "npm install" to install dependencies.
> 4. Run "npm run start" to start the application.

## Usage Information
To use this project, do the following:
> 1. Ensure Installation Steps have been complete.
> 2. For localhost, open browser and browse to URL http://localhost:3000
> 3. You may create transactions, view budget reporting, transactions created while offline will still update the page and transactions will be held in IndexedDB until online, when they will sync with online DB

## Testing
To test this project, do the following:
> 1. To test on Heroku, Ensure Installation steps are complete
> 2. Verify Working on localhost, by performing Usage Steps
> 3. Push your local project to heroku, in terminal run commmand "heroku login"
> 4. Login to your Heroku account in the browser window that pops up, then return to terminal.
> 5. Run command "heroku create my_budget_tracker", to create a heroku app from project
> 6. Verify connection between github and heroku by running command "git remote -v"
> 7. Push code to heroku by running "git push heroku master"
> 8. Login to your Heroku account in web browser and find the app just published.
> 9. Ensure you are signed up to use AtlasDB (Heroku compatible NoSQL DB)
> 10. Ensure you have created a DB in Mongo AtlasDB portal.
> 11. Update the Heroku Config Variables to link to MONGODB_URI for the new DB you created in AtlasDB.
> 12. Select "settings" under your app in heroku browser and scroll down to "Domain" area.
> 13. This is where it lists the domain to your hosted app, click the link to open your app website.
> 14. Test app until satisfied.

## License
This project is provided under the None license. For more information on license details click here [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
## Contributing
If you wish to contribute, do the following:
> Email me directly or submit pull request to contribute.
## Questions
If you have any question about this repo, you may open an issue or contact me directly at jyoung7223@yahoo.com
You can find more of my work at [My Github Repo](https://github.com/JYoung7223 "My GitHub Repo")
## Sample
Deployed project can be found at: https://jy-budget-tracker.herokuapp.com/

Below is a sample screenshot:
![Project Sample](./assets/my_budget.png "Project Sample")
