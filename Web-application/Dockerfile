FROM amytabb/docker_ubuntu16_essentials
COPY WebApp /WebApp
WORKDIR /WebApp/
RUN g++ -o WebApp WebApp.c
CMD ["./WebApp"]

FROM nginx
COPY index.html /usr/share/nginx/html/index.html
