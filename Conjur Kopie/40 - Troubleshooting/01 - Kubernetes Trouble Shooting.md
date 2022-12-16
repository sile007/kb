
Run command inside a container
```bash

kubectl exec -i -t test-app-secrets-provider-k8s-6c67d96d49-l9sm9  -n test-app-namespace --container test-app env
```

Get POD information
```bash

kubectl describe pod/test-app-secrets-provider-k8s-6c67d96d49-l9sm9 -n test-app-namespace
```

Get Logs from POD / Container
```bash

kubectl logs test-app-secrets-provider-k8s-6c67d96d49-l9sm9 -c cyberark-secrets-provider-for-k8s -n test-app-namespace
```

Scale PODs 
```bash

kubectl scale deploy -n test-app-namespace --replicas=1 --all
```


