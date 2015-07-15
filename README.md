# Description
Skeleton application received after performing the `wagtail start hellowagtail` command. I've modified it to include a theme similar to the [time](http://time.com) website.

The master branch has files for the lesson titled: Creating and displaying pages in Wagtail. 

# How to use
- Clone the repository.
```
git clone git@github.com:muthuridennis/wagtail-screencast-hellowagtail.git
```
- Create a virtual environment. I recommend using [virtualenvwrapper](https://virtualenvwrapper.readthedocs.org/en/latest/index.html) to use with [virtualenv](https://virtualenv.pypa.io/en/latest/index.html).
```
mkvirtualenv wagtail-screencast-hellowagtail
```
- Install requirements.
```
pip install -r requirements.txt
```
- Run migrations.
```
python manage.py migrate 
```
- Create a superuser to use when accessing wagtailadmin.
```
python manage.py createsuperuser
```
- Start the server.
```
python manage.py runserver
```


# For windows users
I have a screencast on how to setup wagtail on windows using Vagrant. You can watch it on [Youtube](https://www.youtube.com/watch?v=W1Xt3Z2qUsk).