# docker_demo
docker build -t sandeep_demo . 

docker tag id smendiratta/sandeep_demo
 
upload a image

docker login

# Kubernetes demo
 kubectl run demo --image=smendiratta/sandeep_demo

 kubectl expose deployment demo --port 80 --type LoadBalancer
