# project-seeker
### Run the dev environment app with docker by using
```
docker-compose up
```

### Compiles and minifies for production on NGINX with the build dockerfile
```
docker build -t project-seeker-app-prod -f Dockerfile-build-app .
```

then you can run the container with
```
docker run -itd -p 8080:80 project-seeker-app-prod
```
### If the host machine doesn't have vue installed we can use this to create a new vue project
```
docker build -t vueapp -f Dockerfile-create-app .
```
then we have to run the container with
``` docker run -itd -v ${PWD}:/app --name vueapp vueapp```
and now we create the vue project itself with
``` docker exec -it vueapp vue create my-project```
and finally update permissions with
``` sudo chown -R $USER:$(id -gn $USER) ./*```
### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
