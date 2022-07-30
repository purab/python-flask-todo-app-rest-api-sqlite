## Python todo list - rest api - sample code


* todo list
GET api - http://localhost:5000/todolist


* Create TODO
POST api - http://localhost:5000/todolist
{
    "name":"test",
    "description":"des"
}

* todo list by id - 1
GET by ID - http://localhost:5000/todolist/1

* update by id - 1
Update request
PUT by ID - http://localhost:5000/todolist/1
{
    "name":"test1111",
    "description":"des11111",
    "completed":true
}

* delete by id - 1
DELETE request
DELETE by ID - http://localhost:5000/todolist/1