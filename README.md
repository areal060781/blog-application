# Simple Blog application
A blog application made with **Flask**

* Post CRUD
* User registration, login, logout and reset password using tokens
* Error pages
* Email service
* Upload files and resize pictures

### Requirements
* Python 3.7
* Virtualenv

### Installation
Inside the project folder create the environment, activate it and install the dependencies
```sh
python3 -m venv venv
. twittervotes/bin/activate
pip install -r requirements.txt
```

Copy the config file and edit the variables
```sh
cp flaskblog/config-example.json config.json
```

Run the application
```sh
(venv) $ flask run
```