# aks-e2e-gitops

Etat désiré du cluster AKS, synchronisé par Argo CD.

- `bootstrap/` : installation Argo CD + app racine
- `platform/` : briques plateforme
- `policies/` : policies Kyverno
- `charts/` : chart Helm de l'app
- `apps/<env>/` : values par environnement
