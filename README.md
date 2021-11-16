SIFO SERVER MUSIK PLAYER 

------------------------

This is only copy of project taken from  https://github.com/AshkanGanj/Music-django-app/


some modifiction applye (oprek2 dikit) :D


this is a music server , created with python django :) its like simple spotify server 

==================================

HOW TO RUN IT WITH PYTHON

1. install gnbu linux os

-----------------

2. insatll python3


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


./manage ip:port


examample


./manage 192.168.43.135:3333




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

pyinstaller --hidden-import music.apps --hidden-import music.urls      --add-data "Music_App:Music_App"  --add-binary "Music_App:Music_App"   --add-data "templates:templates"  --add-binary "templates:templates"       --add-data "static:static"  --add-binary "static:static"     --add-data "media:media"  --add-binary "media:media"   --add-data "staticfiles:staticfiles"  --add-binary "staticfiles:staticfiles"     --onedir   manage.py 




======================

4. the binary result in dist/ manage :)


================

thanks :)






