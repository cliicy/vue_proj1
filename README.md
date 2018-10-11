#
Vue.js SPA served over Flask microframework

* Python: 3.6.3
* Vue.js: 2.5.2
* vue-router: 3.0.1
* axios: 0.16.2 我用的是最新版本


## Build Setup

``` windows
# install front-end
cd frontend
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production/Flask with minification
npm run build

https://www.zcfy.cc/article/full-stack-single-page-application-with-vue-js-and-flask-4491.html

# install back-end
cd ../backend
# virtualenv -p python3 venv
# source venv/bin/activate
# pip install -r requirements.txt
pip install -U flask-cors  # Successfully installed flask-cors-3.0.6
cd ..

# serve back-end at localhost:5000
pushd F:\Projects\vTrade\11_10_vue\flaskvue
set FLASK_APP=run.py
set FLASK_DEBUG=1
flask run

```

