# employee-service

git clone https://github.com/vaibhavjain4/employee-service.git -b v1

oc login <url> -u <user>
  
oc project <project_name>

mvn clean package -Dquarkus.kubernetes.deploy=true -Dquarkus.kubernetes-client.trust-certs=true -Dquarkus.openshift.name=employee-service-v1

create route and access http://<route>/employees  
