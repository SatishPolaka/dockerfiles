ARG version
FROM almalinux:${version:-9}
ENV MY_VAR="Hello, World!"\
    Name="satish"

ARG ${username:- deafult}
RUN echo "Hello, ${Name}" > /tmp/hello.txt
CMD ["sleep", "100"]