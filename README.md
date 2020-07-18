# Daily-Journal

This is a blog website made using Node.js, Express, MongoDB, and EJS templating. The home page of the website uses EJS templating to use a for loop to look up all the existing posts and render them to the screen. The Blog Schema consists of a title, content, and a image buffer which is used to store the image. I am using lodash to create custom post routes so that whenever a new post is generated it has its own route where the whole post can be read. The "/compose" route can be used to compose a post and it consists of uploading a file for which I have added verification so that only image files are accepted. I am using multer npm package for image uploading and validation and to optimize performance I use "sharp" npm package to resize images.

## TO RUN: 
You can download the files and open the terminal and go into downloaded folder and run the command "npm i" to install all the required node modules. Then open a new terminal window and run the MongoShell command "mongod" to run the local database. Then run "node app.js" in the first window to run the application on localhost:3000.


### Here's how it looks:-

<img width="1439" alt="Screenshot 2020-07-18 at 1 54 26 PM" src="https://user-images.githubusercontent.com/65245684/87848783-caee0180-c900-11ea-9903-4490ce258fcc.png">
