FROM daocloud.io/library/python:3.4.1-onbuild

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

ONBUILD COPY requirements.txt /usr/src/app/
ONBUILD RUN pip install --no-cache-dir -r requirements

ONBUILD COPY . /usr/src/app
