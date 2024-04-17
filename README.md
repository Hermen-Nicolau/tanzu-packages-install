# tanzu-packages-install
Collection of all the Tanzu packages and YAML files I have used for TKG


Installing and Using VMware Tanzu Packages on Kubernetes v1.26-1.28 - https://docs.vmware.com/en/VMware-Tanzu-Packages/2024.2.1/tanzu-packages/index.html

Prepare to Install Tanzu Packages - https://docs.vmware.com/en/VMware-Tanzu-Packages/2024.2.1/tanzu-packages/prep.html

Add the Package Repository to the Cluster - https://docs.vmware.com/en/VMware-Tanzu-Packages/2024.2.1/tanzu-packages/prep.html#add-the-package-repository-to-the-cluster-2

- imgpkg tag list -i projects.registry.vmware.com/tkg/packages/standard/repo
- kubectl apply -f packagerepo.yaml
- kubectl get packagerepositories -A
- tanzu package repository list -A