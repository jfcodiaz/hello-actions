FROM nginx:alpine as base

RUN echo "Base!" > /usr/share/nginx/html/index.html

FROM base as dev

RUN echo "Dev!" > /usr/share/nginx/html/index.html

FROM base as prod

RUN echo "Hello, Fargate!" > /usr/share/nginx/html/index.html