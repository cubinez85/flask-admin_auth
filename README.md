# устанавливаем  Flask с помощью nginx, supervisor, gunicorn:
https://github.com/cubinez85/flask_site
# или:
https://www.howtoforge.com/how-to-install-flask-with-nginx-and-gunicorn-on-ubuntu-22-04/
# запускаем init б/д:
flask db init
flask db migrate -m 'init'
flask db upgrade
# делаем restart:
sudo systemctl restart supervisor.service
# идем в браузер:
http://www.site.com
