# This dockerfile utilizes components licensed by their respective owners/authors.
# Prior to utilizing this file or resulting images please review the respective licenses at: https://github.com/django/django/blob/master/LICENSE

FROM python:latest@sha256:d3c16df33787f3d03b2e096037f6deb3c1c5fc92c57994a7d6f2de018de01a6b

LABEL Description="Django" Vendor="Django Software Foundation" Version="2.2"

RUN ["pip", "install", "Django==2.2"]

CMD ["django-admin --version"]
