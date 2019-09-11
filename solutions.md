1) 

Request: GET  https://fsw62-todos-api.herokuapp.com/api/users

Body:

Response: {
    "payload": [
        {
            "id": 1,
            "username": "alejo4373"
        },
        {
            "id": 2,
            "username": "JRJRocks"
        },
        {
            "id": 3,
            "username": "Mike923"
        },
        {
            "id": 4,
            "username": "3Chainz"
        },
        {
            "id": 5,
            "username": "George W. Swoosh"
        },
        {
            "id": 6,
            "username": "A pimp named slickback"
        },
        {
            "id": 7,
            "username": "okurrrt"
        },
        {
            "id": 9,
            "username": "AnimalCrackerEater"
        },
        {
            "id": 10,
            "username": " SillyRabbit"
        },
        {
            "id": 11,
            "username": "Stink Meaner"
        },
        {
            "id": 12,
            "username": " theRealObama"
        },
        {
            "id": 13,
            "username": " chrissyteigen"
        },
        {
            "id": 14,
            "username": "\"not alejo4373\""
        },
        {
            "id": 15,
            "username": "jenesh"
        },
        {
            "id": 16,
            "username": "22 Savage"
        },
        {
            "id": 17,
            "username": " Peter"
        },
        {
            "id": 18,
            "username": " test"
        },
        {
            "id": 19,
            "username": "A"
        },
        {
            "id": 20,
            "username": "Lil Thanos"
        },
        {
            "id": 21,
            "username": "Cow"
        },
        {
            "id": 22,
            "username": "Karen123"
        },
        {
            "id": 23,
            "username": "test2"
        },
        {
            "id": 24,
            "username": "Run The Jewels"
        },
        {
            "id": 25,
            "username": "the real not alejo4373"
        },
        {
            "id": 26,
            "username": "sunnyd"
        },
        {
            "id": 27,
            "username": "pecan_breezy"
        },
        {
            "id": 28,
            "username": "kitkatjewels"
        },
        {
            "id": 29,
            "username": " woah"
        },
        {
            "id": 30,
            "username": "Bernie Gang"
        },
        {
            "id": 31,
            "username": "Khan"
        },
        {
            "id": 32,
            "username": "ShaynaRocks"
        }
    ],
    "err": false
}

What does it do?: It gives you a list of all the users. 

2) 

Request: GET https://fsw62-todos-api.herokuapp.com/api/users/JRJRocks

Body: 

Response: {
    "payload": {
        "id": 2,
        "username": "JRJRocks"
    },
    "err": false
}

What does it do?: Gives you all the information for the user with the username JRJRocks

3) 

Request: POST  https://fsw62-todos-api.herokuapp.com/api/users/signup

Body: username : fullStackGuy

Response: {
    "payload": {
        "user": {
            "id": 35,
            "username": "fullStackGuy"
        },
        "msg": "User created"
    },
    "err": false
}

What does it do?: Creates a new user with the username fullStackGuy.

4) 

Request: GET  https://fsw62-todos-api.herokuapp.com/api/todos

Body: 

Response: {
    "payload": [
        {
            "id": "ecf57050",
            "owner": "AnimalCrackerEater",
            "text": "Leave Crackers on the sofa",
            "completed": false
        },
        {
            "id": "33a3ebd0",
            "owner": "jenesh",
            "text": "spread radical candor",
            "completed": false
        },
        {
            "id": "5354dde0",
            "owner": "George W. Swoosh",
            "text": "Invade Iraq",
            "completed": false
        },
        {
            "id": "666",
            "owner": "Cow",
            "text": "Moo some more",
            "completed": false
        },
        {
            "id": "969d7210",
            "owner": "Lil Thanos",
            "text": "Snap Yo Fingers! Do ya steps!",
            "completed": false
        },
        {
            "id": "188b0300",
            "owner": "the real not alejo4373",
            "text": "rip out hair after multiple GET errors",
            "completed": false
        },
        {
            "id": "2f77d8e0",
            "owner": "the real not alejo4373",
            "text": "look over at neighbor's screen to see if they're anywhere better in the lab",
            "completed": false
        },
        {
            "id": "fd3a5dd0",
            "owner": "the real not alejo4373",
            "text": "stare blankly at Postman for minutes",
            "completed": true
        },
        {
            "id": "7b453650",
            "owner": "the real not alejo4373",
            "text": "wish i had the real alejo4373's knowledge",
            "completed": false
        },
        {
            "id": "8feb0260",
            "owner": "the real not alejo4373",
            "text": "find edible food. profit!!!",
            "completed": false
        },
        {
            "id": "7",
            "owner": "okurrrt",
            "text": " ummm idk what to do",
            "completed": true
        },
        {
            "id": "ac30a0d0",
            "owner": "alejo4373",
            "text": "hide birth certificate",
            "completed": false
        },
        {
            "id": "9b110360",
            "owner": "alejo4373",
            "text": " 1st Todo",
            "completed": false
        },
        {
            "id": "129d9b90",
            "owner": "Bernie Gang",
            "text": "Seize the means of production and inhalation ",
            "completed": false
        },
        {
            "id": "31786e60",
            "owner": "Mike923",
            "text": "found who did it !!!!!!!!!",
            "completed": true
        },
        {
            "id": "83f01010",
            "owner": "Stink Meaner",
            "text": "died, I shall return even meaner",
            "completed": true
        },
        {
            "id": "a7a7e790",
            "owner": " woah",
            "text": " idk wtf im doing",
            "completed": false
        }
    ],
    "err": false
}

What does it do?: Gives you a list of all the items the users want to do any whether or not they've been completed.


5) 

Request: POST  https://fsw62-todos-api.herokuapp.com/api/todos

Body: 
    owner:fullStackGuy
    text:clean up 6.1's mess
    completed:false

Response:{
    "payload": {
        "id": "340548e0",
        "owner": "fullStackGuy",
        "text": "clean up 6.1's mess",
        "completed": false
    },
    "err": false
}

What does it do?:  Create a to-do list item for the user fullStackGuy.

6) 
Request: GET  https://fsw62-todos-api.herokuapp.com/api/todos/776f95e0

Body: 

Response: {
    "payload": {
        "id": "776f95e0",
        "owner": "fullStackGuy",
        "text": " worry about whether or not I really understand what's going on",
        "completed": false
    },
    "err": false
}

What does it do?: Retrieves a to-do item by it's id.

7) 

Request: PUT  https://fsw62-todos-api.herokuapp.com/api/todos/776f95e0

Body: 

owner:fullStackGuy
text: worry about whether or not I really understand what's going on
completed:true

Response:{
    "payload": {
        "id": "776f95e0",
        "owner": "fullStackGuy",
        "text": " worry about whether or not I really understand what's going on",
        "completed": true
    },
    "err": false
}

What does it do?: It changes the entire body of the to-do.

8) 

Request: PATCH  https://fsw62-todos-api.herokuapp.com/api/todos/776f95e0

Body: completed: false

Response: {
    "payload": {
        "id": "776f95e0",
        "owner": "fullStackGuy",
        "text": " worry about whether or not I really understand what's going on",
        "completed": false
    },
    "err": false
}

What does it do?: Change one specific key in the the to-do.

9) 

Request: DELETE  https://fsw62-todos-api.herokuapp.com/api/todos/776f95e0

Body: 

Response:
{
    "payload": {
        "id": "776f95e0",
        "owner": "fullStackGuy",
        "text": " worry about whether or not I really understand what's going on",
        "completed": false
    },
    "err": false
}


What does it do?: It deletes that to-do item. It gives you the same response, which is odd, but I tried to get that to-do again (to make sure it was deleted) and it gave me {
    "payload": {
        "msg": "Todo not found"
    },
    "err": true
}

which shows that it really has been deleted.