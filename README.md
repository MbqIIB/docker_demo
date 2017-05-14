### docker_demo

# build
docker build -t sandeep_demo . 

# tag and upload
docker tag id smendiratta/sandeep_demo

```
docker tag 6e26473e4a47 smendiratta/sandeep_demo:v1.0
docker push  smendiratta/sandeep_demo:v1.0
```

# Kubernetes demo
 kubectl run demo --image=smendiratta/sandeep_demo

 kubectl expose deployment demo --port 80 --type LoadBalancer
