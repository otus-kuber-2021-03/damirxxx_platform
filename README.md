# damirxxx_platform
## HW1
Работа выполнена на виртуалке с использованием minikube

1. Разберитесь почему все pod в namespace kube-system восстановились
после удаления. 

служба миникуба запущена systemd юнитом с бинарником /var/lib/minikube/binaries/v1.20.2/kubelet, пока она работает контейнеры запускаются

core-dns использует ReplicaSet

kube-apiserver это манифест в /etc/kubernetes/manifests/

2. Hipster Shop
не запускается из-за отсутсвия переменных окружения
