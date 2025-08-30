FROM python:3.10-slim-buster
# Install python packages
COPY requirements.txt /tmp
RUN pip install -U pip
RUN pip install -r /tmp/requirements.txt
