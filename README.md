# Basic Website Front End Tutorial

This tutorial will take you through the steps of developing a full website. It utilizes html, css, php and javascript/jquery.

**Directory structure**:
```
- css
    - app.css - is where all your styles will reside
- img
    - Contains all the images for the website
- js
    - site.js - contains the javascript for the website 
- lib
    - Contains the global php files that are used throughout the entire site
- process
    - Contains the processing script for the contact form
```

What is a webserver? Really it is just a computer that will serve up the pages of your website. Typically you will have a domain name like domain_name.com that will point to a specific directory on that computer, inside that directory will contain a index.html or index.php file typically. The index file is almost always the main entry point, so if someone goes to http://domain_name.com, the server will look for that index file and serve it to the browser.

As a prequisite I would cover this [basics readme](basics.md), this will cover some basic concepts of html and css that will be directly helpful in the actual tutorial. They are more basic concepts and so they are not part of the full tutorial but will definitely be helpful to understand the tutorial.

Typically your index file will be your homepage, so we'll start there and begin [building out the website](tutorial-assets/tutorial.md).