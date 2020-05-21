`export KUBECONFIG=~/.kube/someconfig`

`kubectl get secrets secretsname -o=yaml`

`kubectl logs --since=20m podname | grep "email"`

`kubectl exec -ti podname bash`

`kubectl describe pod podname`

`kubectl get deployment deploymentname`

`docker run -p 6380:6380 redis`

`git config user.name "Name"`

`openssl aes-256-cbc -md md5 -in secrets.yml.crypt -out secrets.yml -d -base64`

`openssl enc -md md5 -aes-256-cbc -in secrets.yml -out secrets.yml.crypt -e -base64`

`host somedomain`
