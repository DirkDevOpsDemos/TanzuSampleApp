# TanzuSampleApp Demo
Folgede Befehle ausführen um die Demo zu zeigen:

kubectl apply -f https://raw.githubusercontent.com/DirkDevOpsDemos/TanzuSampleApp/main/TanzuSampleApp

kubectl exec -it tanzu-demo-pod-ngix -- bash

cd /usr/share/nginx/html

curl https://raw.githubusercontent.com/DirkDevOpsDemos/TanzuSampleApp/main/index.html -o index.html

exit

kubectl get services

Die Website ist unter der in "External IP" augeführten IP erreichbar...

Ggf. Backround hinzufügen:

curl https://raw.githubusercontent.com/DirkDevOpsDemos/TanzuSampleApp/main/DellDemoTanzu.jpg -o DellDemoTanzu.jpg

<div style="background-image: url('DellDemoTanzu.jpg');">
