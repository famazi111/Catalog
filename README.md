# Item Catalog Application

## Item Catalog is a web application, which allows users to do mainly the following:

* Browse categories,
* Show items in categories and recently added items,
* Show item details
* Authenticate users,
* Enable users to modify their own items

## In order to run the web site, it is required to:

* Download or clone the [fullstack-nanodegree-vm repository](https://github.com/udacity/fullstack-nanodegree-vm).
* Find the *catalog* folder and replace it with the content of this current repository, by either downloading it or cloning it - [Github Link](https://github.com/famazi111/Catalog).
* Locate application.py, database_setup.py files and templates, static folders in the folder */vagrant/catalog*
* Modify client_secrets.json file in order to change application information for Google Plus authentication
* Run ```python database_setup.py``` to setup the database.
* Run ```python initialData.py``` to populate some initial data.
* Run ```python application.py``` to start the application

## Browsing the web site:

* Browse <http://localhost:8000> to view application
* Categories and items may be selected to view in detail
* In order to add new item "New Item" link should be clicked from the navigation menu, if no user logged in, it will redirect to login page
* In order to login click "Click Here To Login" link from the navigation menu
* After logging in, user can add new item
* After logging in, if item detail page browsed, there will be links for Edit and Delete
* For JSON API endpoint visit <http://localhost:8000/catalog.json>
* For XML API endpoint visit <http://localhost:8000/catalog.xml>
