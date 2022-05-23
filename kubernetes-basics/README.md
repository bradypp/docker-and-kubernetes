Deploy
k apply -f web-to-nginx.yaml -f nginx.yaml

Check
k get deploy,svc

Access nginx server through node.js server
localhost:(node-to-nginx port)/nginx
