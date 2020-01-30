# Helpers and scripts used

## Get maven docker image

docker pull maven

## Create maven project

```powershell
docker run -it --rm --name poc_pipeline2020 -v "$(pwd):/usr/src/mymaven" -w /usr/src/mymaven maven mvn archetype:generate -DgroupId="com.telus.poc.web" -DartifactId=java-web-project -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
```

## Docker 



