FROM daocloud.io/library/java:8u40-jdk
RUN  pwd
RUN  ls

COPY /target/mytest.jar /usr/local/

WORKDIR /usr/local

CMD java -jar mytest. jar
