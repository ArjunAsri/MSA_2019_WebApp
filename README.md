
## Usage

Docker was used to create an Image of the app that was pushed to the Azure resource group and used for Web App. I tried with GitHub however, for some reason the app did not respond. There were compile errors due to wrong node modules which were fixed but the app still did not work. 

Link to the App https://msa2019phase1app.azurewebsites.net/

There are 2 screenshots in the repo for the Microsoft Build Simple Website Module.
The link for the Microsoft Build Simple Website Module repo is https://github.com/ArjunAsri/Microsoft-Build-Simple-Website-Module




To run the project, clone the repo, navigate to the root directory, and type `npm install` in a new terminal window.

Once the *node_modules* folder has been created and all the dependencies have been successfully installed. 

Run `npm run start` which will compile the project and allow you to view the app locally.

Note: The project has already been set up with a live reloader. This will compile and reload the web page on your localhost port automatically when you save any file in the project. Therefore, you will NOT have to run `npm run start` every time.

---

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
