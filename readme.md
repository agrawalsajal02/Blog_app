# Blog App Created Using Nodejs Express  MONGODB & Sementic UI 


## Steps to Install
* Clone the Package
* Type "npm install"
* Type net start MongoDB  , make sure mongo server is runnning
* Type "node app.js"
* or Type "npm run start"
* for views html pages try "python -m SimpleHTTPServer 8000"

AUTHOR
```
SAJAL AGRAWAL

NIT PATNA
```




# important notes wile creating this application

'''

* rest stand for representational state transfer
# rest a wy of mapping http and crud together
* it is just  a pattern, it is just a convention or architure of mapping 
# it is pattern of routes that we follow
create
read
update
destroy

'''

7 restfull routes
1)index
2)new
3)create
4)show
5)edit
6)update
7)destroy


### using method overide , beacuse html form do not support put request

### we use sanitizer so that user do not put harmfull script in body of blog
, it shoud always after body parser
npm install method-override

### we are using semaitic ui
### framework for css and javasript
