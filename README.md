Rails Girls App generator 
=========================
```
This app can be used to bootstrap resources in first Rails app.
The app adds comments targeted at Rails Girls students to controllers, models and views etc. 
Like a mini-inline tutorial that explains things briefly and gives pointers to guides or other resources.
```

Steps to create new rails application
-------------------------------------
```
git clone https://github.com/railsgirls-generator-app/railsgirls-app.git

cd railsgirls-app/app
```

Setup instructions
------------------

* Install dependencies 


``` 
bundle install
```
* Create new Controller 


```
rails generate controller <ControllerName>
```
* Create new Model


```
rails generate model <ModelName>
````

* Create new Scaffold

```
rails generate scaffold <FileName>
```

Invoking
--------
```
rails server
```
Open in browser
```
localhost:3000
````


Additional Guides
-----------------
[Rails Girls app tutorials](http://railsgirls-generator-app.github.io/railsgirls-app/ "Digging deeper")

