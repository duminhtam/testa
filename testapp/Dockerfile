FROM java:8-jre-alpine
RUN apk add --no-cache curl tar bash
COPY . /usr/src
WORKDIR /usr/src
RUN tar -xvf testapp.tar
CMD ["java", "-cp", "./testapp.jar", "kixeye.testapp.Main"]
