FROM python:3.6.8-stretch
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
EXPOSE 5000/tcp
COPY . .
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]