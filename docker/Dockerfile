FROM nginx

COPY pass.png/usr/share/ngnx/html
COPY index.html /usr/share/nginx/html/
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
