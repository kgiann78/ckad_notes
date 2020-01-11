## Kubernetes files and notes

This repository holds some notes and files for my CKAD and CKA journey

### Installing MiniKube

Follow instructions from [installing kubernetes](https://kubernetes.io/docs/tasks/tools/install-minikube/)
and all necessary steps installing kubectl and minikube on Ubuntu linux and/or MacOS.

For MacOS I prefer using `Homebrew` but for linux I installed it via direct download: 

    curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
      && chmod +x minikube

This will download the minikube executable. In order to add this executable to your path:

    sudo install minikube /usr/local/bin

Make sure you have installed VirtualBox (you can find information at [drivers](https://minikube.sigs.k8s.io/docs/reference/drivers/))
to use as *vm driver* and then, in order to confirm Minikube installation run

    minikube start --vm-driver=virtualbox

Once `minikube start` finishes check the status of the cluster

   minikube status

To stop minikube run

   minikube stop

And to clean up local state

   minikube delete




