FROM amytabb/docker_ubuntu16_essentials
COPY HelloWorld /HelloWorld
WORKDIR /HelloWorld/
RUN g++ -o HelloWorld helloworld.cpp
COPY script.sh /HelloWorld/script.sh
RUN ["chmod", "+x", "/HelloWorld/script.sh"]
ENTRYPOINT ["/HelloWorld/script.sh"]
