## Docker Commands for profile-management service
### building image
 ```docker build . -t litheshp/profile-managament:latest```
### checking the available images of local machine
 ```docker images```
### running image
```docker run -p 3000:3000 litheshp/profile-managament -d```
### List the containers
```docker ps```

## Minikub
## start
- ```minikube start```
## tunneling
- ```minikube service car-parking-booking-service --url```
## Kubernetes commands 
- ```kubectl create -f deployment.yml```
- ```kubectl get pods```
- ```kubectl get service```
  
  

