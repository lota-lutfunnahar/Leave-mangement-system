### ***Note:*** [Check Wiki for API Documentation](https://github.com/incwell-technology/lms/wiki)
# Steps to run project 
- First make sure you have python install along with pip and virtualenv. Usually pip is installed along python and to install virtualenv: ```pip install virtualenv```  
- clone the repo 
- create virtualenv: ```virtualenv venv``` or ```virtualenv -p python3 venv```
- activate virtualenv: for linux(```source venv/bin/activate```) and for windows(```source venv/Scripts/activate```)
- install django and necessary libraries in venv: ```pip install -r requirements.txt``` (all necessary libraries for project are in requirements.txt file) 
- make neccessary migrations : ```python manage.py makemigrations```
- migrate the files: ```python manage.py migrate```
- create one superuser to access the admin panel: ```python manage.py createsuperuser```
- finally run the project: ```python manage.py runserver```
----- 
# Tools & Technologies Used 
- Django==2.1.5
- django-cors-headers==2.4.0
- pytz==2018.7
- PyYAML==3.13
- Pusher
- djangorestframework==3.9.4
- django-rest-auth==0.9.5
- firebase-admin
- pyjwt==1.7.1
----- 
# Features 
![features](https://github.com/incwell-technology/lms/blob/mobile_api/demo%20images/Leave%20Management%20System%20Use%20Case%20Diagram%20(1).png)

----- 
# Demo 
- Click on the image below to view demo
[![Watch the video](https://github.com/incwell-technology/lms/blob/mobile_api/demo%20images/landing.png)](https://www.youtube.com/watch?v=ea21fa0YxR0&feature=youtu.be)
----- 
# Contribution
The main purpose of this repository is to continue to evolve LMS(Leave Management System) app, making it more easier to use with lots of features. Development of LMS happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving LMS.
In general, we follow the *"fork-and-pull"* Git workflow.

1. **Fork** the repo on GitHub
2. **Clone** the project to your own machine
3. **Commit** changes to your own branch
4. **Push** your work back up to your fork
5. Submit a **Pull request** so that we can review your changes  
**NOTE**: Be sure to merge the latest from "upstream" before making a pull request!
-----
# Leave-mangement-system
