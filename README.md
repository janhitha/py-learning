# py-learning

git init
git add .
git commit -am "Ready for deployment to heroku."
git status

> heroku login
> heroku create
> heroku ps -- To check that the server process started correctly, use the heroku ps command:

heroku open
heroku run python manage.py migrate

heroku run bash
python manage.py createsuperuser



# Deleting a Project on Heroku
heroku apps:destroy --app appname
