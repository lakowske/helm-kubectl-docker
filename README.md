# helm-kubectl-docker

An alpine kubernetes container.  This container has the greatest hits, helm, kubectl and docker.  It also has some other basics
so that a user can clone a git repo.

```bash
# Create a secret and use it to clone a private git repo.

kubectl create secret generic ssh-secret --from-file=ssh-privatekey=$HOME/.ssh/id_rsa --from-file=ssh-publickey=$HOME/.ssh/id_rsa.pub
```



