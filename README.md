Install Node Js 

Angular CLI installation commands

npm install -g @angular/cli
npm uninstall --save-dev angular-cli
npm install


Install mongoDB
start mongo DB with command 
C:\Program Files\MongoDB\Server\3.4\bin>mongod

Start Mongo DB 
insert Records
Add Document - User
/* 1 */
{
    "_id" : ObjectId("5a9fb7f7047f9e3db8b62ec6"),
    "username" : "123",
    "password" : "$2a$10$7alvjhZTxyLpkKGTOnHfLehEyVJbnECMARhbtOC8pzY2Nd8ftjRUC",
    "role" : "admin",
    "__v" : 0
}

/* 2 */
{
    "_id" : ObjectId("5aa628905cf5cd26c0216956"),
    "username" : "shyam",
    "password" : "$2a$10$ZiBfciDCNl1xHenk8yl6eOPRf/nculC2vg8lMGxBXj/DLRONPeca6",
    "role" : "user",
    "__v" : 0
}


Add Document - Book
/* 1 */
{
    "_id" : ObjectId("5a9fdb54c94ffb6e1e06df48"),
    "isbn" : "0812691792",
    "title" : "Autobiographical Notes",
    "author" : "Albert Einstein",
    "publisher" : "Centennial Edition",
    "genre" : "Science",
    "availStatus" : "Not Available",
    "Likes" : 4,
    "Ratings" : 3.5,
    "issueDate" : ISODate("2003-05-13T00:00:00.000Z"),
    "returnDate" : ISODate("2003-05-13T00:00:00.000Z"),
    "renewDate" : ISODate("2018-03-22T10:49:24.162Z"),
    "location" : "R1-C2",
    "issueUserId" : "M1042174"
}

/* 2 */
{
    "_id" : ObjectId("5a9fe1a4c94ffb6e1e06e13f"),
    "isbn" : "0777691792",
    "title" : "A Life of Genius",
    "author" : "Alexander Kennedy",
    "publisher" : "Kindle Edition",
    "availStatus" : "Not Available",
    "genre" : "Science",
    "returnDate" : ISODate("2018-03-13T06:44:38.035Z"),
    "renewDate" : ISODate("2018-03-13T06:52:25.325Z"),
    "issueDate" : ISODate("2018-03-13T06:44:38.035Z"),
    "Ratings" : null,
    "Likes" : null
}

/* 3 */
{
    "_id" : ObjectId("5a9fe1f2c94ffb6e1e06e15d"),
    "isbn" : "0812691792",
    "title" : "Einstein: A Life of Genius",
    "author" : "Alexander Kennedy",
    "publisher" : "Kindle Edition",
    "genre" : "Science",
    "returnDate" : ISODate("2018-03-13T06:59:27.181Z"),
    "renewDate" : ISODate("2018-03-13T06:59:35.802Z"),
    "availStatus" : "Not Available",
    "issueDate" : ISODate("2018-03-13T06:59:27.181Z"),
    "Ratings" : null,
    "Likes" : null
}

/* 4 */
{
    "_id" : ObjectId("5aa790913156070ff422b621"),
    "isbn" : "222222222222222",
    "title" : "Rajapunisha Rara",
    "author" : "Rajapunisha",
    "publisher" : "Rajapunisha Edition",
    "genre" : "Technology",
    "Likes" : 3,
    "Ratings" : 4.5,
    "availStatus" : "Not Available",
    "issueDate" : ISODate("2018-03-13T08:49:21.680Z"),
    "returnDate" : ISODate("2018-03-13T08:49:21.680Z"),
    "renewDate" : ISODate("2018-03-13T08:49:27.783Z"),
    "__v" : 0
}

/* 5 */
{
    "_id" : ObjectId("5aa79105193ab32d607ec4c6"),
    "isbn" : "3333333333333",
    "title" : "Nan Title",
    "author" : "Nan Author",
    "publisher" : "Nan Publisher",
    "genre" : "Technology",
    "Likes" : 3,
    "Ratings" : 4.5,
    "availStatus" : "Not Available",
    "issueDate" : ISODate("2018-03-13T08:51:17.362Z"),
    "returnDate" : ISODate("2018-03-13T08:51:17.362Z"),
    "renewDate" : ISODate("2018-03-13T08:55:21.112Z"),
    "__v" : 0
}

/* 6 */
{
    "_id" : ObjectId("5aa79ee206911833d08b366a"),
    "isbn" : "444444444",
    "title" : "Nan Title",
    "author" : "Nan",
    "publisher" : "Nan Publisher",
    "genre" : "Business",
    "Likes" : 3,
    "Ratings" : 4.5,
    "availStatus" : "Available",
    "issueDate" : ISODate("2018-03-13T09:50:26.179Z"),
    "returnDate" : ISODate("2018-03-13T09:50:26.179Z"),
    "renewDate" : ISODate("2018-03-13T09:50:26.179Z"),
    "__v" : 0
}

/* 7 */
{
    "_id" : ObjectId("5aab7474a8e6bf40941ad997"),
    "isbn" : "43546657657",
    "title" : "eeeeeeeeeeeee",
    "author" : "eeeeeeeeeee",
    "publisher" : "eeeeeeeeeeee",
    "Likes" : 3,
    "Ratings" : 4.5,
    "availStatus" : "Available",
    "issueUserId" : "M1042174",
    "location" : "R1-C2",
    "issueDate" : ISODate("2018-03-16T07:38:28.344Z"),
    "returnDate" : ISODate("2018-03-16T07:38:28.344Z"),
    "renewDate" : ISODate("2018-03-16T07:38:28.344Z"),
    "__v" : 0
}

/* 8 */
{
    "_id" : ObjectId("5aab81ad3629762df072ce42"),
    "isbn" : "999999999999999999999",
    "title" : "sdddf",
    "author" : "sddsfd",
    "publisher" : "dfsdfd",
    "Likes" : 3,
    "Ratings" : 4.5,
    "availStatus" : "Available",
    "issueUserId" : "M1042174",
    "location" : "R1-C2",
    "issueDate" : ISODate("2018-03-16T08:34:53.779Z"),
    "returnDate" : ISODate("2018-03-16T08:34:53.779Z"),
    "renewDate" : ISODate("2018-03-16T08:34:53.779Z"),
    "__v" : 0
}

Start application with "npm start" command
launch localhost:3000



