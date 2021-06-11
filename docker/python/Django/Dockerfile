FROM python:3.6.8-stretch
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
EXPOSE 8000/tcp
COPY . .
CMD [ "python3", "manage.py" , "runserver"]