# CSC-COIN-Project
It is a web based tool where people can upload their creative ideas on the area of their expertise, where other people can rate 
the ideas and talk about feasibility, implementation and work required. 

We intend to bring people together to do things together which could solve or create simplest idea which can be implemented in real
life.  Users : collection to store user records i.e. name, username, password, categories and email.   

Posts : collection to share posts which a user has posted once approved by admin. Also store comments related to posts. Embedded 
doconcept of mongodb.  

AdminPosts : once a user posts an idea it first comes here and admin approves it and then  it goes to posts.   

AdminCategories : The categories which admin can add and user can select from that.

In scope (Phase 1 completed) Registration and Login Posts (verification, updating, counts, rules, category) comment on posts. Add 
categories according to user interest.

Softwares and Technologies used 
Mongodb, nodejs, html,  css, java script, asp.net.

Steps to run the code:
As I did in ubantu 

1. Download nodejs
2. Download npm
3. Download Mangodb
4. Now, go to the directory where the code is present
    Write the following commands in terminal
5.  npm start
6.  mongo
7.  use ideation
8.  db.users.find().pretty();
9. db.admincategories.find().pretty(); 
10. db.categories.find().pretty();
11. db.index.find().pretty();
12. db.index.find().pretty();
13. now, on other terminal type the command : start ideation
14. now, run as localhost:3000/admin/login (in browser for admin to login)
15. then, run as localhost:3000/user (in browser for user)

