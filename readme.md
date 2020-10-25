# Movie Center Web Application

## Description

Set up a web application using Flask framework in python. Libraries like Jinja and WTForms are involved in building the application. Architecture design patterns and principles including repositories, dependency inversion, and single responsibility have been used to design applications. Flask Blueprints are using to maintain the concerns between application functions. Pytest are used to test the whole project.


## Installation

**Use the commands below to install the requirements.txt**

```shell
$ cd MovieCenter
$ py -3 -m venv venv
$ venv\Scripts\activate
$ pip install -r requirements.txt
```

## Virtual environment
Set up the virtual environment in Pycharm.
When using PyCharm, set the virtual environment using 'File'->'Settings' and select 'Project:MovieCenter' from the left menu. Select 'Project Interpreter', click on the gearwheel button and select 'Add'. Click the 'Existing environment' radio button to select the virtual environment. 

## Execution

**Running the application**
Use the command "$ flask run" to run the application


## Configuration

The *MovieCenter/.env* file set variables and values corresponding to those variables. 

* `FLASK_APP`: Entry point of the application (should always be `wsgi.py`).
* `FLASK_ENV`: The environment in which to run the application (either `development` or `production`).
* `SECRET_KEY`: Secret key used to encrypt session data.
* `TESTING`: Set to False for running the application. Overridden and set to True automatically when testing the application.
* `WTF_CSRF_SECRET_KEY`: Secret key used by the WTForm library.



 ## Testing
 
 Set the value of `TEST_DATA_PATH` to the absolute path of the *MovieCenter/tests/data* directory to satisfy the requirements of testing the file *MovieCenter/tests/conftest.py*

 Run the tests by using the command "python –m pytest" within the virtual environment.

