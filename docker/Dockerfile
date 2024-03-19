FROM nginx

COPY /usr/share/ngnx/html
COPY index.html /usr/share/nginx/html/
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
