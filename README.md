# Movie Magic Rest API

My Heroku account is not able to authenticate against GitHub using OAUTH. Hence,
I am creating a separate repo for this on Heroku.

Note that Heroku will run the app using `npm start`. So the start script should
run the prod build.

## Deploy using Heroku Git

$ heroku login

Make some changes to the code and deploy them to Heroku using Git.

```shell
git add .
git commit -am "make it better"
git push
```

The API will be available at https://movie-magic-api.herokuapp.com.
