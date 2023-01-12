#### FLASK RESTX BOILER-PLATE WITH JWT BUILD ON PYTHON 3.9

### Terminal commands
Note: make sure you have `pip` and `virtualenv` installed.
    To run test: flask test

    To run application: flask run


Make sure to run the initial migration commands to update the database (from the venv!).

    > export FLASK_APP=manage.py
    
    > flask db init

    > flask db migrate

    > flask db upgrade


### Viewing the app ###
    Open the following url on your browser to view swagger documentation
    http://127.0.0.1:5000/


### Using Postman / Insomnia ####
    Authorization header is in the following format:

    Key: Authorization
    Value: "token_generated_during_login"

    For testing authorization, url for getting all user requires an admin token while url for getting a single
    user by public_id requires just a regular authentication.


### Based on : Full description and guide (beware this guide targets an older python version!) ###
https://medium.freecodecamp.org/structuring-a-flask-restplus-web-service-for-production-builds-c2ec676de563

