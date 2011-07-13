express-shisoconf11 is website for Shiso Conference 2011 with Node
------------------------------------------------------------------

### Prerequisite
- Node
- npm
- heroku
-- If you needs to deploy to Heroku by yoursefl
- gem
-- If you wants to test with Procfile

### Try 
``` 
$ git clone git@github.com:Shisobu/express-shisoconf11.git
$ npm install
```

### Development
Feel free to push.

### Test
#### Local
##### just Node
```
$ node app.js
```
##### With Procfile
```
$ gem install foreman
$ foreman start
```

After that, access ://localhost:3000 to check your app.

#### Staging
```
$ heroku create
$ git push heroku master
$ heroku open
```

### Production
How to deploy
-> Ask to @marutanm
