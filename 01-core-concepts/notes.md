 etcd key value store 
does not have schema 
does not support complex queries
perdormance is super fast
very flexibilbe and simple fast lookup

intslla etcd manually
 download the binarry
 extract.
 run etcs service

 listens to port 2379 by defauls

 etcdctl put key value to store key
 retrive etcdctl get

 etcd runs nodes,pods,configs,secret,account,roles,binding 

kubeadm disploy etcd server as a pod in a kube namespace




kube apiServer primary management componnt in kubernetres

authenticate user
valiadate request
retrieve data
update etcd
scheduler
kubelet


kube controller manager
  process contionously monitor the state of various component in  within sysyem and works towards bringing the whole syeyte to the desired state


  node controller 
  node monitoes perios 5 m
  node monitore grace perios is 40 mns 
  pod evistion timeout  5 mins

  kube scheduler
  responsible for scheduling for pods and nodes only decide which pod goes where or which nodes the pod are assigned to


  schedulere 
  filters the nodes
  rank nodes

  kubelet is an agent that registers the node,create pods and minitors state of nodes and pods

  kube proxy is the pod network


  yaml in kubernetes
  apiVersion v1
  kind :pod
  metadata :
    name: myapp-pod
    labels:
        app :myapp
  spec:
    containers:



   


