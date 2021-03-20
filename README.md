# kuber_dz3
1)Create cluster and start work with it
gcloud container clusters create levelup
gcloud container clusters get-credentials levelup
2)Clone git@github.com:elenarazguliaeva/kuber_dz3.git and create deployment, autoscaling and service
kubectl apply -f homework.yml
3)Get external IP and check if everything run successfully
kubectl get services
e.g curl 34.82.253.202
