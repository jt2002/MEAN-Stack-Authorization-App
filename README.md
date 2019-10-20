# MEAN Stack Authorization App
Codes of MEAN stack (MongoDB-Express-Node-Angular6) of Traversy Media's YouTube tutorial "MEAN Stack Front To Back"

### Requirements

- Heroku account
- mLab account
- Locally installed Git

### Pre-Upload to Heroku

Update confi/database.js for the database in mLab, i.e.

```
mongoURI: 'mongodb://abcdefg:abcdefg@ds123456.mlab.com:56789/meanauth-dev'
```

### Upload to Heroku

Note the URL when running ```heroku create```

```
git init
git add .
git commit -am "initial commit"
heroku create
git push heroku master
```

### Sample Live App

```
https://infinite-springs-40564.herokuapp.com/
```
