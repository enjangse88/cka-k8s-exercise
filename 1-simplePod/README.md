kubectl create -f pod.yaml

kubectl expose pod webapp --port=80 --name=webexpose
