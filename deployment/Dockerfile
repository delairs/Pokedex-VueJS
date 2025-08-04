FROM nginx:alpine

# Salin semua file dari repository-mu ke dalam folder web server Nginx
COPY ./index.html /usr/share/nginx/html
COPY ./img /usr/share/nginx/html/img

# Beritahu Docker bahwa kontainer akan berjalan di port 80
EXPOSE 80