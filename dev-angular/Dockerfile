FROM nginx:1.17.1-alpine

WORKDIR /angularApp

COPY . /angularApp

COPY ./dist/frontend/ /usr/share/nginx/html

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 4200