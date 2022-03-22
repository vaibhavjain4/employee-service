# employee-service

git clone https://github.com/vaibhavjain4/employee-service.git -b v2

oc login <url> -u <user>
  
oc project <project_name>  

mvn clean package -Dquarkus.kubernetes.deploy=true -Dquarkus.kubernetes-client.trust-certs=true -Dquarkus.openshift.name=employee-service-v2

create route and access http://<route>/employees 
