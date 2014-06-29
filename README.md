## KMAN
<strong>K</strong>oa + <strong>M</strong>ongoDB  + <strong>A</strong>ngular.js + <strong>N</strong>ode.js

A starting point for writing AngularJS apps backed by a Koa-powered node.js server.

### Requirements
1. MongoDB
2. node >= 0.11.9
3. ruby and sass,compass gems
4. git


In addition, __Linux__ or __Mac__ is optional but recommended, because __Linux__ or __Mac__ is more friendly to ruby(& gems) and some npm packages.

### For Develop

    npm install -g bower grunt-cli
    npm install
    bower install
    grunt dev

Then the default browser will open <http://localhost:3000> automatically.

A livereload server was started by grunt-contrib-watch which will watch static files(css, js, html) and server(via nodemon).

So, if you want to refresh your browser when you changed specific files, maybe you should install the [browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-).

### For Deploy

    npm install --production
    npm start

### LICENSE
MIT