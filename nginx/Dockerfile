FROM nginx:1.15.0

#? REMOVE A CONFIGURACAO PADRAO DO NGINX
RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/conf.d/default.conf
