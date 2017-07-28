# dash-heroku-multiple-routes
Boilerplate code for a deployment-ready dash app with multiple routes and scikit-learn through anaconda environment.

## Python 3.5 version

```bash
git add .
git commit -m"Personalized version"
git push origin master
git push heroku master


git push -u origin --all
heroku create MY_UNIQUE_APP_NAME
heroku config:add BUILDPACK_URL=https://github.com/arose13/conda-buildpack.git
git push heroku master
```

The running example can be found at:

[https://dash-routes-heroku-example.herokuapp.com/](https://dash-routes-heroku-example.herokuapp.com/)
[https://dash-routes-heroku-example.herokuapp.com/first](https://dash-routes-heroku-example.herokuapp.com/first)
[https://dash-routes-heroku-example.herokuapp.com/second](https://dash-routes-heroku-example.herokuapp.com/second)


## Python 2.7 version
```
heroku config:add BUILDPACK_URL=https://github.com/kennethreitz/conda-buildpack.git
```