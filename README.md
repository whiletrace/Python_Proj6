# Mineral Catalogue [![Build Status](https://travis-ci.com/whiletrace/mineral_catalogue.svg?branch=master)](https://travis-ci.com/whiletrace/mineral_catalogue)
## summary
This is a django  built dynamic app that displays minerals <br/>attributes,
current mineral attributes displayed: 

* name
* image filename
* image caption
* category
* formula
* strunz classification
* color
* crystal system
* unit cell
* crystal symmetry
* cleavage
* mohs scale hardness
* luster
* streak
* diaphaneity
* optical properties
* refractive index
* crystal habit
* specific gravity
* group

filters on:

Glossary A-Z, Mineral Group, text search (contained within name)

data can be found at **./data/minerals.json**
site caontains: minerals list and minerals detail

 ### built on:
 * python  3.5
 * django  2.1.7
 * pytz 2018.2
 
 **additionally included for heroku deployment**
 * dj-database-url 0.5.0
 * gunicorn 19.9.0
 * psycopg2-binary 2.8.1
 * whitenoise 4.1.2
 
 ### to run locally:
 * clone repo and cd to root dir
 * suggested that you run virtualenv
 * pip install **-r requirements.txt** within shell
 
 ### create db tables and migrate data
 *  run **python manage.py makemigrations**
 *  run **python manage.py migrate** 
 
 ### start server
 *  run **python manage.py runserver 8000**
 ## to run tests:
 * run manage.py tests
