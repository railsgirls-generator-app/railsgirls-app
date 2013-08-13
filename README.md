Rails Girls App generator 
=========================

This app can be used to bootstrap resources creating your first Rails app. It adds comments to steps in the Rails Girls guide, explaining what's going on in more detail. 
The Rails Girls App generator works like a mini-inline tutorial that gives pointers to other guides or additional resources, without cluttering what should be an easy-to-go-through document.


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
Run
```
rails server
```
And open in your browser
```
localhost:3000
````


Additional Guides
-----------------
[Rails Girls app tutorials](http://railsgirls-generator-app.github.io/railsgirls-app/ "Digging deeper")

