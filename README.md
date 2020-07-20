# Simple Blog application
Simple blog application made with Flask

### Includes
* Post CRUD
* User registration, login, logout and reset password using tokens
* Error pages
* Email service
* Upload files and resize pictures

### Requirements
* Python 3.7
* Virtualenv

### Installation
```sh
git clone https://github.com/areal060781/blog.git
cd blog
python3 -m venv venv
pip install -r requirements.txt
```

Edit the variables
```sh
cp flaskblog/config-example.json config.json
```

Run the application
```sh
(venv) $ flask run
```