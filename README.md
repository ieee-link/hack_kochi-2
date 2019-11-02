# hack_kochi#2 PS1

Create a very simple todo application using the Angular and Node.
1) Create a node express project with three routes to:
    - POST
    - GET
    - PUT
    - DELETE
2) Now create a .json file in a project directory, using below format, which should be created by node app when it starts for first time if the file doesn’t exist.

 {
    “author”: <your name>, <— this should be added when the files is created first time
    “version”: <This should be pulled from your package.json file using your code and inserted here> <— this should be added when the files is created first time
    “time_stamp”: <date and time when the file was created in this format eg “18 June 2019 at 9:00 AM”>, <— this should be added when the files is created first time
    “to_do_list”: [<to_do_objects here>, <to_do_objects here>] <- this array should consist of all the todo objects
 }
3) Now using all above 4 routes to write below content inside the .json file you created just now.
    a) Using one of the 4 routes you should add 5 todo items to the above json file to_do_list array with a success response on you API.
    b) Using one of the 4 routes you retrieve all todo items from the above json with status 201.
c) Using one of the 4 routes you should remove 3rd position todo items in the above json with status 204.d) Using one of the 4 routes you should update 2nd position todo items name with “new text” in the above json with status 204.
e) Now make a copy of json file as “_yourjsonfilename.json” at the same location and add a name/value pair “updatedAt”:<time this copy file was created>.
        And attach the file to email when you send this task to back
4) Create a angular app with a table displaying all the content from JSON file using your API you created
    a) Create a page where you can add todo items using one of your API.
    b) add edit button to you last column of your row which will should edit the item at that location.
    c) add delete button to you last column of your row which will should delete the item at that location.
5) Now attach the final .json file in the email.
6) Now make an angular build using AOT now copy the dist folder to your node project and make a new route in node app and render the index.html using the new route.
7) Now make two zip of your project one node project as “NODE- FINAL.ZIP” and angular project as “ANGULAR-TASK.ZIP”.
8) (OPTIONAL) BONUS QUESTION - Create and postman collection to test your api and the collection link here.

END OF TASK HERE

This to keep in mind:
1. DO NOT INCLUDE node modules FOLDER IN THE ZIP2. 
2. If you are not able to complete all you can send whatever you can completed and mention the email which you have completed
3. Before you send check:
    1. Your attachment has “_yourjsonfilename.json”
    2. Your attachment has final “.json”
    3. Your attachment has NODE-FINAL.ZIP
    4. Your attachment has ANGULAR-TASK.ZIP
    5. List of question you have completed

This task will be evaluated on below basis.
    1. Folder structure.
    2. Cleanness of code.
    3. Logics you use.
