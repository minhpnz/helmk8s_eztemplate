# helm-library

libchart project contains the Helm library chart </br>    
development project contains the Helm application chart </br>

## Commands
- helm package libchart/    
- helm dependency update development/ 
- helm template nginx ./development -f development/application/nginx.yaml #Preview template
- helm install nginx ./development -f development/application/nginx.yaml #Deploy

- helm template nginx ./development -f development/application/busybox.yaml #Preview template
- helm install nginx ./development -f development/application/busybox.yaml #Deploy