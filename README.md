kubectl create secret generic regcred --from-file=.dockerconfigjson=/root/.docker/config.json --type=kubernetes.io/dockerconfigjson


Replace docker URL in pipelineresources.yaml 

kubectl apply -f tekton/
