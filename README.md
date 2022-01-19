# rohanjson



# Hi I use a put command in my database code is


{

"token": "708862679|8981615562961411263|268862579",
    "cmd": "PUT",
    "dbName": "Employeer",
    "rel": "index",
    "colsAutoIndex": false,
    "templateStr": {
        "name": "Omkar Wable"
    },
    "jsonStr": {
        "name": "Omkar Wable",
        "email": "OmkarWable@gmail.com",
        

    }
}





# 2. I use a update command
{



    "token": "708862679|8981615562961411263|268862579",
    "cmd": "UPDATE",
    "dbName": "Employeer-DB",
    "rel": "Employeer",
    "jsonStr": {
       "3":{
        "full_name": "Shree Mehta",
        "email_address":"Shree@gmail.com",
        "mobile_number": 7845962546

      },
       "6":{
        "full_name":"Ganesh Naik",
        "email_address":"ganeshnaik@gmail.com",
        "mobile_number": 1234567891
      },
       "5":{
        "full_name":"Omkar Wable ",
        "email_address":"Omkar@gmail.com"
      }
   }
}



# 3 I use a remove command

{

    "token": "708862679|8981615562961411263|268862579", 
    "cmd": "REMOVE",
    "dbName": "Companys",
    "rel": "Employeer",
    "record": 1
    
}
