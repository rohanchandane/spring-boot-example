1. Created a dockerfile
2. Pushing the docker image to Docker Hub
    - Create a tag before pushing it to Docker Hub https://stackoverflow.com/questions/41984399/denied-requested-access-to-the-resource-is-denied-docker
    - create a docker tag `docker tag spring-boot-example rohanchandane/spring-boot-example`
    - check if new tag is created `docker images`
    - login to docker hub `docker login -u [username]`
    - push to docker hub `docker push rohanchandane/spring-boot-example`
