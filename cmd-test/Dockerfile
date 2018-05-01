FROM openjdk:9

LABEL author=Neeraj 

RUN mkdir build 

COPY mypack build/mypack

ENTRYPOINT ["java", "-cp", "build", "mypack.Adder"]

CMD ["10","20"]
