FROM openjdk:11
EXPOSE 8080
COPY ./tp-docker-1.0.0.jar /
ENV db_url=127.0.0.1:5432/tp_devops username=tp_devops password=tp_devops
CMD java -Ddatabase.url=$db_url -Ddatabase.username=$username -Ddatabase.password=$password -jar tp-docker-1.0.0.jar