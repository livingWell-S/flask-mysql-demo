FROM python:latest
ADD ./src/ /code
ADD ./requirements.txt /code
WORKDIR /code
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD ["python", "run.py"]