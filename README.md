# Strapi application

A quick description of your strapi application

<a href="https://www.heroku.com/deploy/?template=https://github.com/co3coin-finance/strapi-heroku-template">
<img src="https://assets.strapi.io/uploads/Deploy_button_heroku_b1043fc67d.png" />
</a>

Be aware that one of the content type builder won't work due to the writing files restriction on the Heroku servers. If you do want to change content types, you need to follow these steps:

1. Click the button above and deploy your app
2. Clone that repo by using `heroku git:clone -a ` followed by your repo's name
3. Go into the cloned projects' folder using `cd` followed by your repo's name
4. Add the Heroku boilerplate as a remote by running `git remote add master https://github.com/co3coin-finance/strapi-heroku-template`
5. Pull from this new origin by running `git pull master`
6. Deploy your application `git push heroku master`
