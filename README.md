# Demo Project: MongoDB and MongoExpress
Via: [Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]](https://www.youtube.com/watch?v=X48VuDVv0do&t=4576s)

![Browser Request Flow through the K8s components](https://github.com/alcardm/k8-demo-project/raw/main/flow-throught-k8s-comp.jpg)
To deploy:
1. `kubectl apply -f mongo-secret.yaml`
2. `kubectl apply -f mongo.yaml`
3. `kubectl apply -f mongo-configmap.yaml`
4. `kubectl apply -f mongo-express.yaml`

To verify:

✔ `kubectl get all`

✔ `kubectl logs mongo-express-NAME`

✔ `kubectl get service`


To assign external-IP on *minikube*

👉`minikube service mongo-express-service`

🍕