# user1info
JavaScript code to test automatically response's body for user #1

Attached 3 files: JavaScript code (which I used in Postman), Json file (exported from Postman), HTML report file.

I used Postman to create the call request to the relevant endpoint.  
I wrote the tests in Postman's "tests" tab (for the relevant EP) using JavaScript. 
It is possible to run the test with Postman by importing the Json file.
Via cmd and Newman, I am able to run the collection without Postman ("newman run user1info.json").  
In addition, I can use this command "newman run user1info.json -r cli,json,junit,html", and Newman will create a HTML report. 
Both reports will show how many iterations were made, how many tests were executed and how many of them passed/failed.
In the file I attached to the email youll be able to see the cmd report screenshot in case you dont have Newman installed in your machine.
