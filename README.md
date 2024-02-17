[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/skooner)](https://artifacthub.io/packages/search?repo=skooner)

# skooner-helm
A Helm Chart to deploy [Skooner](https://github.com/skooner-k8s/skooner)

## Installation
```
helm repo add skooner https://kube-the-home.github.io/skooner-helm/
helm install skooner/skooner
```

## Access Token
To access te skooner WebUI you need to get the access token:

``` kubectl describe secret skooner-secret -n <your_skooner_namespace> ``` 


## Documentation
- [All](https://kube-the-home.github.io/kube-the-home/)
- [Contributing](https://kube-the-home.github.io/kube-the-home/Contribution/)
- [Helm Chart](https://kube-the-home.github.io/kube-the-home/Helm-Charts/skooner/)
