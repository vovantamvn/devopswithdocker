FROM python:3.9

WORKDIR /usr/src/app

COPY django-dictionary .

EXPOSE 8000

RUN pip install -r requirements.txt

RUN python manage.py migrate

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000"]
