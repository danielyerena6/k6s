FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY jenkins.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
CMD ["nginx"]
