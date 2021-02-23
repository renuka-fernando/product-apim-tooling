## apictl k8s add api

Handle APIs in kubernetes cluster 

### Synopsis

Add, Update and Delete APIs in kubernetes cluster. JSON and YAML formats are accepted.
available modes are as follows
* kubernetes

```
apictl k8s add api [flags]
```

### Examples

```
apictl k8s add/update api -n petstore --from-file=./Swagger.json --replicas=3 --namespace=wso2
```

### Options

```
  -f, --from-file string   Path to swagger file
  -h, --help               help for api
  -n, --name string        Name of the API
      --namespace string   namespace of API
```

### Options inherited from parent commands

```
  -k, --insecure   Allow connections to SSL endpoints without certs
      --verbose    Enable verbose mode
```

### SEE ALSO

* [apictl k8s add](apictl_k8s_add.md)	 - Add an API to the kubernetes cluster
