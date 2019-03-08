# cluster-configuration
## TODO:
- [x] Add Kubernetes flannel network overlay
- [ ] Include PXE config
- [ ] Include Ansible play for pxe server, http, pxe
- [x] Include Ansible play for Kube-master
- [x] Include Ansible play for Kube-agents
- [x] Refactor to be in line with [best practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html)
- [x] Research mechanism for passing cert hash generated by cluster to ansible [SEE](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-join/)
- [ ] Create and enable service for `kubectl proxy` on kubemaste
- [ ] Create nginx reverse proxy for dashboard
