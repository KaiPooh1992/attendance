FROM python:3.10.6

WORKDIR /VSCODE

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY ./Flask_app ./Flask_app

CMD [ "python", "Flask_app/app.py" ]