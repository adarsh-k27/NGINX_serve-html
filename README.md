# STEPS TO SERVE HTML FILE

1. Change Directory to Nginx `cd Nginx`
2.  Build  an Image with a name based upon docker file  `docker build -t nginx-html .`
3.  Run  Container with image  nginx-html and portmap to 3050 `docker run -it -p 3050:80 nginx-html`
4.  check with localhost:3050
