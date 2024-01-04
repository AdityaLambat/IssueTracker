# IssueTracker

Developed a dynamic and responsive full-stack web application using Node.js and EJS for efficient issue tracking and project management.
Implemented advanced filtering options, allowing users to filter issues by multiple labels, author, and search by title and description for enhanced project detail exploration.


## Deployed On
**Render**

## Hosted Link
https://issuretracker.onrender.com/

## Features

1. Allows users to create detailed issues, including a title, description.
2. Assigns issues to specific team members or individuals responsible for addressing them.
3. Tracks the status of each issue.
4. Allows the categorization of issues with labels or tags (e.g., bug, enhancement, documentation).

## Technologies Used

The IssueTracker is build using the following technologies:

<p>
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/HTML.svg" width="50">
  <img src="https://github.com/tandpfun/skill-icons/raw/main/icons/CSS.svg" alt="CSS Icon" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/raw/main/icons/JavaScript.svg" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/React-Dark.svg" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/ExpressJS-Dark.svg" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/MongoDB.svg" width="50">
</p>

## Getting Started

To set up the API on your local machine, follow these steps:
````
1. Clone the repository.
2. Install the packages using npm

````

### After reaching the project directory you have to run the following command.
````
 node index.js

````

### Folder Structure

````
Issue Tracker
  ->|           
    |---> assets --->|
    |                |---> js --->|
    |                             |---> filterissues.js
    |                             |---> searchissues.js
    |                  
    |---> config --->|
    |                |---> mongoose.js
    |
    |---> controllers --->|
    |                     |---> home_controller.js
    |                     |---> project_controller.js
    |             
    |---> models--->|
    |               |---> issue.js
    |               |---> project.js
    |
    |---> routes --->|
    |                |---> index.js
    |                |---> project.js
    |
    |---> views --->|
    |               |---> partials --->|
    |                                  |---> home.ejs
    |                                  |---> layout.ejs
    |                                  |---> project_page.ejs
    |             
    |---> README.md
    |---> index.js
    |---> package-lock.json
    |---> package.json

    ````
