# K3s
- Make by Rancher Labs

## 1. Khái Niệm
- K3s phiên bản nhẹ của Kubernetes.
- Giải pháp slim K8s.
- Sử dụng cho:
 - Edge
 - IoT
 - CI
 - Development
 - ARM
 - Embedding K8s
 - Chạy được trên Rashberry Pi
 
## 2. What is K3s
- Các packaged dạng single binary packaged
- Storage dựa trên sqlite3 làm default database. Etcd3, MySQL cũng tồn tại.abs
- Chia làm 2 phần K3s server và agent (dạng kiểu master node và workernode trong k8s) 
-  Có thể chạy single node
- Remove dependency on docker 
- Remove dependency on etcd
- Replacing docker with containerd
- Yêu cầu 512MB Ram và 200MB dung lượng ổ đĩa
- Helm chart cũng hỗ trợ K3s
- Không support High Availability (HA)
- 

 ![](https://k3s.io/images/how-it-works-k3s.svg)

 ![](https://www.jambit.com/site/assets/files/10220/minikube-kind-k3s-local-kubernetes-cluster-1.-squaremedium.jpg)


