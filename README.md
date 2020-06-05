# Blog application
Flask blog application

## Modules
* Post
    * create
    * read
    * update
    * delete
* User
    * register
    * login
    * logout
    * reset password

Include
* Error pages
* Email service
* Upload files and resize pictures
* Reset password tokens 

### Requirements
* Python 3.7
* Virtualenv

### Installation
```sh
git clone https://github.com/areal060781/blog.git
cd blog
virtualenv env
pip install requirements.txt

cp flaskblog/config-example.json config.json
```