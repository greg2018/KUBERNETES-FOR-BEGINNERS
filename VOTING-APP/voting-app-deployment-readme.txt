Steps of deployment
#Step-01)
kubectl create -f voting-app-deployment.yml
kubectl create -f voting-app-service.yml

#Step-02)
kubectl create -f redis-deployment.yml 
kubectl create -f redis-service.yml

#Step-03)
kubectl create -f postgres-deployment.yml
kubectl create -f postgres-service.yml

#Step-04)
kubectl create -f worker-app-deployment.yml

#Step-05)
kubectl create -f result-app-deployment.yml
kubectl create -f result-app-service.yml


#Others for reference
 postgres-pod.yml
 redis-pod.yml
 result-app-pod.yml
 voting-app-pod.yml
 worker-app-pod.yml