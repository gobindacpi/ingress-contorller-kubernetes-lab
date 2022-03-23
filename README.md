# ingress-contorller-kubernetes-lab

Please Note:

nginx-ingress.yaml

~~~
here - path: / nginx2 will not work by default, because nginx default extention is index.html, if we set nginx2.html insted of index.html then will work .  

to change this follow below instruction. 

Step 1: kubectl -n ingress-nginx exec -it nginx2-644bf9b4cf-rrx29 /bin/bash
cd /usr/share/nginx/html/ 
mv index.html nginx2.html
~~~
