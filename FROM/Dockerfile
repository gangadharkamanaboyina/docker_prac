FROM nginx
RUN "rm -rf /usr/share/nginx/html/index.html"
COPY "config/index.html" "/usr/share/nginx/html/"
CMD ["nginx", "-g", "daemon off;"]