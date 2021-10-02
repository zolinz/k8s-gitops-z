# k8s-gitops-z



my cluster to sync with flux


flux bootstrap github \
--owner=zolinz \
--repository=k8s-gitops-z \
--path=k8s/clusters/raspbernetes \
--personal


flux bootstrap github \
--owner=zolinz \
--repository=k8s-gitops-z \
--path=k8s/clusters/raspbernetes,k8s/namespaces,k8s/workloads \
--personal
