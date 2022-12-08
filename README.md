# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver

Todo-list
=======

sudo pip3 install virtualenv
mkdir ~/newproject
cd ~/newproject
virtualenv newenv
source newenv/bin/activate
git clone url
pip install django
vi todoApp/setting.pyls
Give acess to allowed host ['*']
Timezone--Dhaka

python3 manage.py runserver
python3 manage.py migrate
python3 manage.py runserver 0.0.0.0:8000
vi Dockerfile
sudo docker buil -t todo-app .
sudo docker run -p 8000:8000 image id

url:8000---running
Jenkins setup
===================
sudo apt update
sudo apt install default-jre
java --version
sudo apt install jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
check in brower by ip adress:8080

No need all these just use

*sudo docker pull jenkins/jenkins
*sudo docker run -d -p 8080:8080 docker.iojenkins:latest
Register in it

create an agent
give path in remote directory /home/ubuntu
and save it

Go to Dashboard-->Build Steps-->execute shell--> cd /home/ubuntu/newproject/django-todo

Give permission chmod 777 django-todo

sudo docker build . -t todo-dev
sudo docker run -d -p 8000:8000 todo-dev

Build It








```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
