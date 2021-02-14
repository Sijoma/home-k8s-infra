# home-k8s-infra


## Seal secrets so that the cluser can use them

```
kubeseal --format=yaml --cert=pub-sealed-secrets.pem \     
< any-secret.yaml > any-secret-sealed.yaml
```