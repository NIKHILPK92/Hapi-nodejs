# Hapi-nodejs
* Skipping nodemodules
* Download the ZIP
* just run npm install
* START Application by npm start
* Changes will be updated by nodemon package
* Simple project have 2 APIs GET and POST
* Details given Below



APIs
# 
GET
*http://localhost:3020/git?search=nodejs&offset=1&numResults=50
GET API for retriving all repostories that contributing to nodejs 
In GET API, default search is nodejs, you can change the search name  
http://localhost:3020/git?search=express&offset=1&numResults=50 
Dynamic search and pagination is used for better result
Handlebarjs used for creating table view for the GET API result*


# POST
*http://localhost:3020/listToTree
POST API Must have payload
POST API will convert the Flat json to Tree array (parent-children)
Algorithm is Perfect for the same format JSON
It will return Tree array*

# **

*Written by
*NIKHIL PK

# **
