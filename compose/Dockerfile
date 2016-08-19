FROM python:3-alpine
add requirements.txt /requirements.txt
RUN pip install -r requirements.txt
ADD . /code
WORKDIR /code

CMD python app.py