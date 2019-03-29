# Notes à destination des développeurs

* Lancer le navigateur sans les CORS (pour usage local) : 

``` bash
open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security
```

* Lancer le server flask 

``` bash
cd flask/directory/
export FLASK_APP=app.py
flask run
```

* Lancer le server ionic 

``` bash
cd ionic/directory/
nmp install
ionic serve
```