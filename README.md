# Coursera Front-End JavaScript Frameworks Overview: Angular Assignments

This is the assignments repository for Coursera's Front-End JavaScript Frameworks Overview: Angular course. You can access the course [here](https://www.coursera.org/learn/angular).

## Table of Contents
1. [Installation](#installation)
2. [Important Note](#important-note)
3. [Serving REST Content](#serving-rest-content)
4. [Static Web Server](#static-web-server)

## Installation <a name="installation"></a>

In order to run the assignments, you will need to have Node.js and Angular CLI installed. Follow these steps:

1. **Node.js**: Download and install Node.js from [nodejs.org](https://nodejs.org/).

2. **Angular CLI**: Install Angular CLI globally by running this command in your terminal:

```
npm install -g @angular/cli
```

3. **Project Dependencies**: After cloning this repository, navigate to the 'conFusion' folder and install the project dependencies:

```
npm install -g @angular/cli
```

## Important Note <a name="important-note"></a>

Please note that this repository is intended for information and audit purposes only. It is not meant to be used for copying assignments if you are also taking the course. Always follow the course's academic integrity guidelines.

## Serving REST Content <a name="serving-rest-content"></a>

You can serve REST content using 'json-server.' Follow these steps:

1. Install 'json-server' globally by running this command:

```
npm install -g json-server
```

2. Navigate to the 'Assignment 4/conFusion' folder in your terminal window.

3. Start the 'json-server' by running this command to introduce a 2-second delay before responding to requests:

```
json-server --watch db.json -d 2000
```

## Static Web Server <a name="static-web-server"></a>

The 'json-server' also provides a static web server. Resources placed in a folder named 'public' in the 'json-server' folder will be served by the server at the following address:

[http://localhost:3000/](http://localhost:3000/)

Feel free to explore the assignments and course material. Happy learning!

---

**Note**: Please ensure that you have the required software and dependencies installed as mentioned above to work with this repository.
