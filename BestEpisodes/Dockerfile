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

# Expose the default ports
EXPOSE 8000
EXPOSE 5000

# Start nginx
ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:5000"]