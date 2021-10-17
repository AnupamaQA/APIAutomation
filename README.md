# APIAutomation
APIAutomation project using Postman.

GitHub Repository details for API Automation:

repository name:API Automation
Clone URL: https://github.com/AnupamaQA/APIAutomation.git

Automation Tool:
Postman tool is used for scripting API automation.Newman is used as command line runner for execution of postman scripts.
Follow the below steps to run the scripts in local.

1) Clone the repository 
2) Download and install Postman app
3) Import the JSON file to postman
4) Import the Global variables JSON data file
5) Click on the collection and select Run Collection

Command line execution:
1) Install NodeJS
2) Create a package.json file and install "newman" node module
3) 'npm install newman --save'  for installing newman
4) Navigate to project directory 
4) Run the command : "newman run Challenge.postman_collection.json -g global_variables_v1.json"

Integration with Jenkins:
1) Create a new item of type freestyle project 
2) Navigate to configure. Provide SCM details - git URL and credentials 
3) Add windows batch shell commands as Post build step - "npm install & npm run apitest"
4) Kick off build

UI Automation :
I have not completed this part of the assignment. Most of my past experience is on backend automation and I do not have experience in Front end UI automation.
However, I have started exploring Selenium, BDD-Cucumber, Specflow. Its still early phase of learning and I tried creating a project with specflow, but figured out, I need to compelte my learning cycle and only then I can build projects.

