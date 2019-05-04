# kubernete.sh

Deploy "throw-away" Kubernetes Cluster(s)

## tl;dr

````
$ kubernete.sh 
kubernete.sh v0.1.0
https://github.com/brotandgames/kubernete.sh

Usage: kubernete.sh [command]

Commands:
  deploy       Deploy a Kubernetes Cluster
  token        Get Kubernetes Dashboard Token <sensitive>
  proxy        Creates a proxy between localhost and the Kubernetes API Server
  print_nodes  Print node configuration in HCL (for Debugging)
  version      Print version
  *            Help

````

````
$ kubernete.sh deploy
== kubernete.sh 2019-05-03T18:46:14Z ERROR: No nodes argument found.
Command: 
  kubernete.sh deploy

Usage: 
  kubernete.sh deploy node1[,node2,nodeN] [ssh_private_key_path]

Examples:
  kubernete.sh deploy root@n1.kubernete.sh
  kubernete.sh deploy root@n1.kubernete.sh,root@n2.kubernete.sh ~/.ssh/id_rsa
````

## Maintainer

https://github.com/brotandgames