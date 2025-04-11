# Test deployment GZAC
Deze repository is niet meer dan een test-deployment van [GZAC (Generiek Zaakafhandelcomponent)](https://gzac.gitbook.io/product-docs) in een lokaal Minikube cluster. Ik gebruik ArgoCD om de [Helm Charts](https://github.com/generiekzaakafhandelcomponent/helm-charts) te deployen.


## ArgoCD
Zie mijn [argocd-demo repository](https://github.com/boonchris/argocd-demo) of [ArgoCD: Getting Started](https://argo-cd.readthedocs.io/en/stable/getting_started/#1-install-argo-cd) voor informatie over ArgoCD.

## Deployen van GZAC
Na het installeren en configureren van ArgoCD:
```bash
kubectl apply -f https://raw.githubusercontent.com/boonchris/argocd-demo/main/app-of-apps.yaml
```