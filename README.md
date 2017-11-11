# Overview
This is a basic show-case project to a News feed mini-site in ReactJS (with mini-server for it implemented in node.js).

# Running the News Mini-Site
To try the mini-site on your local machine, you should act as follows

- make sure all of the software platforms and packages are pre-installed and properly configured on your machine (see _Installation and Configuration_ section below)
- download or clone this repository to a local folder of your choice
- open a command-line prompt utility and navigate to the above-mentioned local folder
- start the server backend via the command: _npm start_
- go to http://localhost:4061/ in any browser

Once you do it, you will be able to
- see the initial list of three news publications in the feed
- add new posts with news at your discretion

# Installation and Configuration

Below are the important pre-requisites you should complete on your machine before you can run the News Mini-Site there

- Install **node.js** platform on your local machine (download the right package for your platform at https://nodejs.org/en/download/ as well as follow the respective installation instruction)
- Install **express** package into your **node.js** platform as a global package via the command: _npm install express -g_

# Known Issues and Limitation

- as this project is a basic show-case, the functionality to persist (store) the new news posts has not been implemented - thus the new posts you add will not be serialized and displayed after you restart the server