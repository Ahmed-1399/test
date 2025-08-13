FROM nginx:alpine

COPY ./static_website/ /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

