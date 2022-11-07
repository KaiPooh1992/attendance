FROM python:3.10.6

WORKDIR /Project_Devops

RUN pip3 install -r requirements.txt

COPY ./Flask_app ./Flask_app

CMD ["python", "Flask_app/app.py"]