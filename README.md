# TanzuSampleApp Demo
Folgede Befehle ausführen um die Demo zu zeigen:

kubectl apply -f https://raw.githubusercontent.com/DirkDevOpsDemos/TanzuSampleApp/main/TanzuSampleApp

kubectl exec -it tanzu-demo-pod-ngix -- bash

cd /usr/share/nginx/html

curl https://raw.githubusercontent.com/DirkDevOpsDemos/TanzuSampleApp/main/index.html -o index.html

exit

kubectl port-forward tanzu-demo-pod-ngix 8080:80
