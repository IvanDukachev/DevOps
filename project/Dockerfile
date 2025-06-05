FROM nginx:alpine

COPY nginx-config /etc/nginx/conf.d/
COPY index.html /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]