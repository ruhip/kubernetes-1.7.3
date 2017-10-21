# Kubernetes
----
##### You have a working [Go environment].

```
$ go get -d k8s.io/kubernetes
$ cd $GOPATH/src/k8s.io/kubernetes
$hack/update-codecgen.sh
$hack/update-generated-runtime.sh
$hack/update-generated-protobuf.sh
$ make
```
