docker pull jenkins/jenkins

docker run --restart=always -d -p 8080:8080 --name=jenkins_container jenkins/jenkins

docker logs container-name

eg docker logs jenkins_container

You wil find password here  