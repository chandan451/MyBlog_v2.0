Clone This Project (Make Sure You Have Git Installed)
```
https://github.com/chandan451/MyBlog.git
```
Install Dependencies 

```
pip3 install Django==2.1
pip3 install gunicorn
pip3 install whitenoise
pip3 install dj-database-url
pip3 install psycopg2
pip3 install pytz
```
*Add you secret key for encryption in the secret_key.txt file

*Change the Database details as per your local Database in /blog_project/settings.py

Set Database (Make Sure you are in directory same as manage.py)
```
python manage.py makemigrations
python manage.py migrate
```
Create SuperUser 
```
python manage.py createsuperuser
```

After all these steps, you can start testing and developing this project and can directly host it in any hosting platform. 

#### That's it! You are ready to go, Happy Coding!
