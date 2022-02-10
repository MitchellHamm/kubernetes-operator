# kubernetes-operator

## To generate:

`make manifests`
`make generate`

## To build + push
`make docker-build docker-push`

## To deploy resources to k8s
`make deploy`

## To test to reconciler
`kubectl apply -f memcached_crd.yaml`