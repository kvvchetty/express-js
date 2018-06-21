# express-js
EJS static page server
<<<<<<< HEAD


Express is a framework to create a website with Node. Just like any website creation, the first step to create an Express website is to set up an template and routing. EJS is an easy templating language to generate HTML with Javascript. It works well with Node without having to learn more complicated front-end frameworks like Angular or React.

Another important component in Express is the Router class which is a middleware to make url path-based routing easy and maintainable.

Here the demo is to create a 3-page websites with home, about and contact pages with header, nav and footer templates and routing traffic by the express server. 

Project Folder

Create a main project folder and run npm init -y. Then, organise it as below.

-- project_folder
 -- css
    -- style.css
 -- html
    -- about.ejs
    -- contact.ejs
    -- index.ejs
    -- include
        -- footer.ejs
        -- head.ejs
        -- nav.ejs
        -- scripts.ejs
 -- routes
    -- index.js
 -- app.js
 -- package.json
 -- package-lock.json
 -- node_modules
Packages

Dependencies are below. For the front-end, we will use bootstrap 4 which requires jquery and popper.js. The ejs package for creating template.

"dependencies": {
    "bootstrap": "4.0.0",
    "ejs": "2.6.1",
    "body-parser": "1.18.3",
    "express": "4.16.3",
    "jquery": "3.3.1",
    "popper.js": "1.12.9"
}

Please see the folder for code content.

=======
>>>>>>> a1376bdd2f22abe114096b7a222c718cee89f1c5
