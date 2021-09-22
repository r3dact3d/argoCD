project: default
source:
  repoURL: 'https://github.com/r3dact3d/argoCD.git'
  path: base/rhacm
  targetRevision: rhacm
destination:
  server: 'https://kubernetes.default.svc'
  namespace: open-cluster-management
syncPolicy:
  automated:
    selfHeal: true
