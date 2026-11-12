# EFK-stack-deployment-by-me

commands 

for killerkoda
kubectl port-forward svc/elasticsearch 9200:9200 --address 0.0.0.0
kubectl port-forward svc/kibana 5601:5601 --address 0.0.0.0
