# Dockerfile to build iot webserver
# Based on debian with nginx installed

# Set the base image to nginx
FROM django:onbuild

# File Author / Maintainer
MAINTAINER sawaiz@sawaizsyed.com

# Install any required packages
# RUN pip install requirements.txt

# Working directory
WORKDIR /usr/src/app

# Start nginx
ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:5000"]