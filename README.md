# Data-model
basic-level
GitHUb Basic : 
web architecutre
Data mode;
we need asysytem to manage all tema members to control the code 
VCS : 
github kinda cloud service to vshare your code with others 
Git is a application can be install on your machine
index.html : 
style.css :
now add all these tow to the GIT : push this ti GIT / push a command to GIT 

GIT comes with Linux 


Data-modeling 

Github : central repository to keep your code with all histories and help you to seethe changes happend on your code. 

milestone delivery: 
**infra-structure- artictechure : **
Client server: your laptopb serve as a client , my data was js on my machine as well. no one expect me can use it. 
Multiple client can use now my code if I use : 
client - show data to user  - like moblile application or web application 
differnc: website and web application : 
web application can be dowloaded to our laptop and website can not be 
 website it a static html -css js attach it 
it is not conncted with data base 
Web appl are connected to external APIS 
we need a data-base for all web app, and we need a server to take care of responses, 
now we are using firebase , it is not the best practoce, we are not using server, we can directly connected to firebase , server can hold all keys, 
Node js and 
google apli keys are not github 
with repository pricare you can also d0 
Local storage session stprage ? save user login to the local storage. is bounded to the URL> 
login .html and dashboar.html 
user will do the login and the data of the user will be saved on the local storage and that user can use in all pages the same id login


+++++
Data-model 
aaplication session storage 
backend - what is the foramt they wnat 
frontend 
they should be agree on the same data-model to create the exat what they are looking for 
(Trello/ Asana) 
wht is table in SQL : 
1 users user-table : user ID user statue Joinedon 
row owns the data of each column 
this is a SQL of TABLE : 
this is called normalizing the data 
denormalizing also its important 

2 Teams now create a another table and find the relation between the user and the teams 
now user can be a columni in teams in this table , each user has a array and save the users inside the table 
Primary key and foreing key 

3 Tasks 
4 perform the real time updarte 
Anaylizing the requirments fisrt 
Then fields we need for the requirement 
SQL NoSQL   ;
we work with collections and Documents : 
all data keeps like a jason format 
Now user collection/userid: 
{
name : string 
Emaol: string
PHOTOurl: string 
Teams" : array []
}
a single user will have dirrefent propertise each of them are called propertise in my user collection 

temas/teamid {
name: 
admin: user id
members: [ will have multiple user ids ]

}
teams/{teamsid}/project{projectID}
project's collection{

name: 
Description: 
member: []
atatus : 

}
....until there/ tasks/{taskid}
tasks collection {
title: 
decription
status
decide
}


