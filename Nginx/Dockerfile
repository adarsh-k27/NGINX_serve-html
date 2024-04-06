FROM nginx
COPY index.html /home/adarsh/Desktop/Docker/serve-html/Nginx/index.html
COPY style.css  /home/adarsh/Desktop/Docker/serve-html/Nginx/style.css
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
RUN nginx -t 