To run automation tests please follow steps listed below:

* Install latest version of Nodejs from https://nodejs.org/en/download/
* Run "npm install -g newman"
* Run "npm install -g newman-reporter-html"
* Download project repository
* Open Console and change directory to project folder
* Run "newman run Adjust_Test_Collection.postman_collection.json -e Adjust_Environment.postman_environment.json -r cli,html" in Console.
