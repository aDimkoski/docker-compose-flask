FROM python:3-onbuild

COPY . /

RUN pip install -r requirements.txt && pip install gunicorn

ENTRYPOINT ["/runserver.sh"]
