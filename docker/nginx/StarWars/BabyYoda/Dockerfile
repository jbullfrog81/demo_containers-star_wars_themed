FROM nginx

LABEL version="0.2"
LABEL description="Star Wars Baby Yoda themed docker image"
LABEL maintainer="https://github.com/jbullfrog81"

# Create a static directory to hold our static files
RUN mkdir /usr/share/nginx/static

# Copy all of our files to their respective nginx directories
COPY ./files/static /usr/share/nginx/static/
COPY ./files/html /usr/share/nginx/html/

# Recursively copy all the etc nginx configuration files to their respective location in /etc/nginx
COPY ./files/etc/nginx /etc/nginx/


EXPOSE 80/tcp
