# imara
This is a template build on Procedural PHP that enables you to register and login users. Once a user is logged in, they are directed to the homepage which contains a welcome message with the users name and a logout button to kick users out.

![screenshot](imara.png)

## Getting Started/Setup

* `git clone this repo https://github.com/ngala21/imara.git`

*move the project from your downloads folder to the htdocs directory

##### Run the Project
* import register.sql to create the database otherwise connection will fail.
* Open MAMP/XAMPP
* Start Apache & MYSQL servers
* Go to your browser and enter the url localhost/auth


 I don't have any application installed to run php😐

#### Install PHP Application 

* brew install MAMP (if you are on macOS)
* Go to chrome and search for XAMPP (if you are on windows)

### Environment requirements 

*DB_HOST = "localhost"
* DB_USER= database user of choice
* DB_PASSWORD= database of choice
* DB_HOST="127.0.0.1" on local
* MODE= dev or prod , set to prod during production
* ALLOWED_HOSTS='.localhost', '.127.0.0.1' 


## Running the tests

Run tests by running the following :

(venv)$ `python3.6 manage.py test photos`

### Break down into end to end tests

The tests will test the following features in the system :

*  Image Model
*  Location and Category models & methods in the models
*  Image Model Methods
*  Search Functionality
*  Image Details
*  Copy link functionality

### And coding style tests

The app does not need coding style tests according to its current scope


## Built With

* PHP
* HTML5
* CSS

## Deployment 

Please read [Deploy to Heroku :)](hhttps://simpleisbetterthancomplex.com/tutorial/2016/08/09/how-to-deploy-django-applications-on-heroku.html) for details on our deployment of this app

## Authors

* **Ngala21** - *Initial work* - [Robot](https://github.com/ngala21)


