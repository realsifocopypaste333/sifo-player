SIFO SERVER MUSIK PLAYER 

------------------------

This is only copy of project taken from  https://github.com/AshkanGanj/Music-django-app/


some modifiction applye (oprek2 dikit) :D


this is a music server , created with python django :) its like simple spotify server 

==================================

HOW TO RUN IT WITH PYTHON

1. install gnu linux os

-----------------

2. install python3

and create virt env 

we can use conda / mini conda


-------------------------

3. clone this project

git clone


-------------------------

4. insatll all the necesaries modul

pip instal -r req.txt


------------------

5. run standart python django command

a. python manage.py migrate

b. python manage.py collectstatic


c. python manage.py createsuperuser


d. python manage.py runserver


open in web browser

127.0.0.1


127.0.0.1/admin



==============================

=====================

HOW TO RUN BINARY WITHOUT PYTHON 



This is only binary ,that compile with pyinstaller, taken from  https://github.com/AshkanGanj/Music-django-app/

so we dont need to install and install python, django etc :)

this is python django music server like simple spotify :D

===============

how to do

1. git clone the repo





-------------

2. navigate to dist

cd dist/manage



3. run manage in terminal /cli in gnu linux os 


a. create data base

./manage migrate

------------------------

b. collectststatic

./manage collectstatic

------------------------

c. create super user

./manage createsuperuser


d. run the server

./manage runserver


open with web browser (firefox, chromium / libre wolf etc)


or 


./manage runserver ip:port


examample


./manage runserver 192.168.43.135:3333




for admin

127.0.0.1/admin

192.168.43.135/admin 


we can edit the song, add songs, remove the songs etc in admin :)


=================




TO COMPILE 


1. clone this project

git clone


--------------------


2. install req.txt

pip install req.txt


================

3. to compile

pyinstaller --hidden-import music.apps --hidden-import music.urls      --add-data "Music_App:Music_App"  --add-binary "Music_App:Music_App"   --add-data "templates:templates"  --add-binary "templates:templates"       --add-data "static:static"  --add-binary "static:static"     --add-data "media:media"  --add-binary "media:media"   --add-data "staticfiles:staticfiles"  --add-binary "staticfiles:staticfiles" --hidden-import music.apps --hidden-import music.urls  --hidden-import  music.apps.MusicConfig  --hidden-import  django.contrib.admin  --hidden-import django.contrib.admin.apps   --hidden-import django.contrib.auth  --hidden-import  django.contrib.contenttypes  --hidden-import django.contrib.sessions  --hidden-import django.contrib.messages --hidden-import django.contrib.staticfiles  --hidden-import django.middleware.security.SecurityMiddleware  --hidden-import django.contrib.sessions.middleware.SessionMiddleware  --hidden-import django.middleware.common.CommonMiddleware  --hidden-import django.middleware.csrf.CsrfViewMiddleware  --hidden-import django.contrib.auth.middleware.AuthenticationMiddleware  --hidden-import  django.contrib.messages.middleware.MessageMiddleware  --hidden-import django.middleware.clickjacking.XFrameOptionsMiddleware       --add-data "static:static"  --add-binary "static:static"     --add-data "media:media"  --add-binary "media:media"   --add-data "staticfiles:staticfiles"  --add-binary "staticfiles:staticfiles" --hidden-import music.apps --hidden-import music.urls  --hidden-import  music.apps.MusicConfig  --hidden-import  django.contrib.admin  --hidden-import django.contrib.auth  --hidden-import  django.contrib.contenttypes  --hidden-import django.contrib.sessions  --hidden-import django.contrib.messages --hidden-import django.contrib.staticfiles  --hidden-import django.middleware.security.SecurityMiddleware  --hidden-import django.contrib.sessions.middleware.SessionMiddleware  --hidden-import django.middleware.common.CommonMiddleware  --hidden-import django.middleware.csrf.CsrfViewMiddleware  --hidden-import django.contrib.auth.middleware.AuthenticationMiddleware  --hidden-import  django.contrib.messages.middleware.MessageMiddleware  --hidden-import django.middleware.clickjacking.XFrameOptionsMiddleware  --hidden-import django.template.backends.django.DjangoTemplates  --hidden-import django.template.context_processors.debug  --hidden-import django.template.context_processors.request  --hidden-import django.contrib.auth.context_processors.auth  --hidden-import django.contrib.messages.context_processors.messages  --hidden-import django.db.backends.sqlite3  --hidden-import django.contrib.auth.password_validation.UserAttributeSimilarityValidator  --hidden-import  django.contrib.auth.password_validation.MinimumLengthValidator   --hidden-import  django.contrib.auth.password_validation.CommonPasswordValidator  --hidden-import django.contrib.auth.password_validation.NumericPasswordValidator  --hidden-import  admin.site.register    --hidden-import  django.contrib  --hidden-import django.apps --hidden-import django --hidden-import django.db  --hidden-import  django.db.models.signals  --hidden-import  django.dispatch  --hidden-import    django.urls  --hidden-import  django.contrib.auth.models  --hidden-import django.contrib.auth.decorators --hidden-import django.core.files.storage --hidden-import jinja2 --hidden-import pillow  --add-data "music:music"   --add-binary "music:music"  --onedir   manage.py





======================

4. the binary result in dist/ manage :)


================

thanks :)






