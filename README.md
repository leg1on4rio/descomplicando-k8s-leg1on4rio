# descomplicando-k8s-leg1on4rio

estudos sobre k8s na linuxtips com o badtux

## Requerimentos

Instalar kubectl https://kubernetes.io/docs/tasks/tools/
Instalar docker desktop (windows version) https://www.docker.com/products/docker-desktop/
Instalar kind https://kind.sigs.k8s.io/docs/user/quick-start/

## Instruções para criar cluster no kind

kind create cluster --config day1/kind/cluster.yaml --name cluster-giropops
