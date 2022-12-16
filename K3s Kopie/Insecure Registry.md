
On each node and master you need to create the following yaml:

path: /etc/rancher/k3s/registries.yaml
if the directory k3s and the file not exists, you need to create it

```yaml
mirrors:
  "192.168.6.53:5000":
    endpoint:
      - "http://192.168.6.53:5000"
```

