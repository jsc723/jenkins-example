# jenkins-example

## Command to run:
```
docker run -u root --rm -d -p 8080:8080 -p 5000:50000 -v "C:/Docker/Jenkins":/var/jenkins_home -v //v ar/run/docker.sock:/var/run/docker.sock --name jenkins jenkinsci/blueocean
```
