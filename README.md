## Kubernetes files and notes

This some notes hold for the CKAD and CKA journey

### Installing MiniKube on Ubuntu linux

Following instructions from [kubernetes.io](https://kubernetes.io/docs/tasks/tools/install-minikube/)

    curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
      && chmod +x minikube

This will download the minikube executable. In order to add this executable to your path:

    sudo install minikube /usr/local/bin

This will do the job, unless you want to use the one you downloaded instead.

In that case you have to edit your `~/.bashrc` (or `~/.bash_profile`) file to export the path of the executable.


