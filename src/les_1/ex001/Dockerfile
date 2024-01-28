FROM bellsoft/liberica-openjdk-alpine:11.0.16.1-1
COPY ./src/les_1/ex001 ./src/les_1/ex001

RUN javac -sourcepath .src -d ./out ./src/les_1/ex001/Main.java
RUN java