## kubernetes 相关镜像无法从google上下载，通过dockerhub+github曲线救国

## 镜像名称	                                             k8s v1.7 版本相关	k8s v1.8 版本相关
gcr.io/google_containers/kube-apiserver-${ARCH}	            v1.7.x	             v1.8.x  
gcr.io/google_containers/kube-controller-manager-${ARCH}	  v1.7.x	             v1.8.x  
gcr.io/google_containers/kube-scheduler-${ARCH}	            v1.7.x	             v1.8.x  
gcr.io/google_containers/kube-proxy-${ARCH}	                v1.7.x	             v1.8.x  
gcr.io/google_containers/etcd-${ARCH}	                      3.0.17	             3.0.17  
gcr.io/google_containers/pause-${ARCH}	                    3.0	                 3.0  
gcr.io/google_containers/k8s-dns-sidecar-${ARCH}	          1.14.4	             1.14.4  
gcr.io/google_containers/k8s-dns-kube-dns-${ARCH}	          1.14.4	             1.14.4  
gcr.io/google_containers/k8s-dns-dnsmasq-nanny-${ARCH}	    1.14.4	             1.14.4  
  
### 注意，这里 v1.7.x和v1.7.x 意思是 你安装的k8s的具体版本。  

### ${ARCH} 指的是具体架构，可选值有: amd64, arm, arm64, ppc64le or s390x  这里只提供amd64，其他的自行解决。
