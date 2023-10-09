FROM openjdk:8-jdk

WORKDIR /test/java

COPY . /test/java/

RUN javac calc.java

CMD ["java", "calc"]