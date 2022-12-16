Get ConjurConfig Map:

```bash

kubectl get configmap conjur-configmap -o "jsonpath={.data}" -n cyberark-conjur

```



```json
{

	"authnK8sAuthenticatorID":"dev-cluster",
	"authnK8sClusterRole":"conjur-clusterrole",
	"authnK8sServiceAccount":"conjur-serviceaccount",
	"conjurAccount":"sima",
	"conjurApplianceUrl":"https://conjur-follower.cyberark-conjur.svc.cluster.local",
	"conjurSslCertificate":"Public SSL Certificate"
}
```

