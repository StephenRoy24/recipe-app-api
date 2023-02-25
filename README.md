# Recipe App API Project

## Description
This project was created using Python and the Django REST Framework alongside Docker. The API allows users to create and update user profiles, upload and store images, and create, filter, and search for objects.

### Steps to Run
1. Clone the repository
2. Run docker-compose up in the command line
3. In your browser go to - http://127.0.0.1:8000/api/docs/
4. Once in the Swagger UI follow the below steps to create and authenticate a user
5. Scroll down to User -> api/user/create -> Click Try it out
    1. Enter the requested information -> Execute
    2. Below in api/user/token -> Click Try it out
    3. Enter credentials created above and you'll receive a token
    4. Copy that token and scroll to the top -> Click Authorize
    5. Scroll down to the third option "tokenAuth" and type the work Token followed by a space, then paste your token code
        1. It is important to add a space after the word token or else it will not authorize
      
    6. Click Authorize and close the window, you're all set!
6. You're now free to use the API to Get, Put, Patch, or Delete: ingredients, recipes, images, and tags
7. Have fun and enjoy!
