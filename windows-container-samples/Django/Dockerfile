# This dockerfile utilizes components licensed by their respective owners/authors.
# Prior to utilizing this file or resulting images please review the respective licenses at: https://github.com/django/django/blob/master/LICENSE

FROM python:latest@sha256:86b2fe5e3cf5b979f4b21849ad340762f4a15129583c8134c6c2dc4a880942e6

LABEL Description="Django" Vendor="Django Software Foundation" Version="2.2"

RUN ["pip", "install", "Django==2.2"]

CMD ["django-admin --version"]
