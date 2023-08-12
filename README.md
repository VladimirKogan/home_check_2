# home_check_2

'kubectl create namespace devops'

'kubectl apply -f service-account.yaml'

'kubectl apply -f deployment.yaml'

// got into Jenkins via node IP and port

// Install kuberenetes plugin
// Add Git and docker creds

// Configure Jenkins and cloud for k8s (namespace, url, tunnel)

create pod temlpate (kube-agend, same devops namespace)
create container template

# creating Pipeline

create pipeline SCM for pulling from git
In pod container dotnet should build application
and docker push to docker hub and in the end 
'kubectl rollout restart deployment/dotnetcore-deployment -n arca'

