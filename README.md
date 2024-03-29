# Musica
# What is Musica?  
Musica is an application that let's you upload, store, and play all of your music from the cloud. You can now manage and listen to your music from any device, anywhere in the world.
# How does it work?
To get started, first create a new album. When adding an album cover logo, it's best to have a resolution of at least 512x512 and to use common image formats such as JPG, JPEG, or PNG.
# Adding Songs
After an album is created you will then be able to add/upload songs. Currently supported file types are WAV, MP3, and OGG.
# My Songs
Once songs are added to an album you are then able to play, favorite, and delete them.
# Searching
You can also search for music using the search feature at the top of every page. Any relevant albums will appear at the top of the results page, and the results for individual songs will appear below. 


## Steps to install and run in local system:-
* Create a virtual environment ```$python3 -m venv <env_name>```
* Activate virtual environment ```$source <env_name>/bin/activate```
* Install requirements in venv ```$pip install -r requirements.txt```
* Make migrations ```$python manage.py makemigrations```
* Apply migrations ```$python manage.py migrate```
* Create a superuser ```$python manage.py createsuperuser```
* Run the server ```$python manage.py runserver```
