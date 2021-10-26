= Give GitOps application controller cluster-admin

''''
oc project openshift-gitops
''''

''''
oc adm policy add-cluster-role-to-user cluster-admin -z openshift-gitops-argocd-application-controller
''''
