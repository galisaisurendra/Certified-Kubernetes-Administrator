## KUBERNETES CLUSTER ARCHITECTURE ##

<img width="1178" alt="image" src="https://github.com/user-attachments/assets/8b2bea62-6365-4767-b0d5-079c1a2139a8">



## ETCD will store below configs ##

* All the metadata and each and every details about k8s cluster will store in ETCD and ETCD will be updated once the change is completed i.e.,, updating the replicas , deleting deployment etc.,,

<img width="1180" alt="image" src="https://github.com/user-attachments/assets/4e8ad968-f673-4345-bb47-fc8a1f45de37">

* we can setup etcd in 2 ways :
  1. Manually
  2. Using Kubeadm - Through kubeadm the ETCD will be deployed as pod in the kube-system namespace
 
<img width="1189" alt="image" src="https://github.com/user-attachments/assets/6951cdaa-aafe-4c50-989c-c017192b65ab">



## KUBE-API Server ##

<img width="1510" alt="image" src="https://github.com/user-attachments/assets/921761af-76cf-483d-ae46-20b06229fe08">


