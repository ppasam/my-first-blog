git github
https://tutorial.djangogirls.org/ru/deploy/

myvenv\Scripts\activate
deactivate

django-admin.exe startproject mysite .

python manage.py runserver

git remote add origin https://github.com/ppasam/my-first-blog.git
git push -u origin master

Развертывание
git status
git add --all .
git status
git commit -m "Changed the HTML for the site."
git push

$ cd ~/<your-pythonanywhere-domain>.pythonanywhere.com
$ git pull

Виртуальное окружение на сервере и обновление статических файлов
$ workon <your-pythonanywhere-domain>.pythonanywhere.com
$ python manage.py collectstatic

python manage.py shell


