# DjangoIntro
Connecting Plotly with Django

* Create an virtual env

i. Check if you have a virtual `env virtualenv --version`
ii. (Not Installed) Dont see a version number? run `sudo pip install virtualenv`
iii. (Installed) Make a folder within the highest file of the project `mkdir ~/env`
iv. run virtualenv `~/env/my_new_app`
v. cd into the bin folder `cd ~/env/my_new_app/bin`
vi. activate the `env source activate`

* `pip install -r requirements.txt`

* Create a Postgres Database & connect it within the plotly_django_tutorial.py settings

* `python manage.py makemigrations`

* `python manage.py migrate`

* `python manage.py runserver`


