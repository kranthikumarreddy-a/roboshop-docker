FROM nginx:1.24.0
RUN rm -f /user/share/ndinx/html/index.html/
RUN rm -f /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf 
COPY static  /user/share/ndinx/html/