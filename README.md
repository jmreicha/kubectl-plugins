# kubectl-plugins

A repo for tracking various kubectl plugins.

# Getting started

For instructions on installing and using kubectl plugins, start with the [Kubernetes docs](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/).

Creating plugins is easy, follow the instructions in the [sample-cli-plugin](https://github.com/kubernetes/sample-cli-plugin) repo for creating your own plugins.

# Plugins

* [krew](https://github.com/GoogleContainerTools/krew) - Package manager for kubectl plugins
* [ksniff](https://github.com/eldadru/ksniff) - Plugin to ease sniffing on kubernetes pods using tcpdump and wireshark
* [kubectl-exec-all](https://github.com/jpdasma/kubectl-exec-all) - Plugin to execute a command in all running pods of a resource
* [kubectl-sudo](https://github.com/postfinance/kubectl-sudo) - Run kubernetes commands with the security privileges of another user
* [kubectl-open-svc-plugin](https://github.com/superbrothers/kubectl-open-svc-plugin) - Plugin that opens the Kubernetes URL(s) for the specified service in your browser
* [kubectl-view-serviceaccount-kubeconfig-plugin](https://github.com/superbrothers/kubectl-view-serviceaccount-kubeconfig-plugin) - Plugin that shows a kubeconfig to access the apiserver with a specified serviceaccount
* [kubectl-kubesec](https://github.com/stefanprodan/kubectl-kubesec) - Plugin for scanning Kubernetes pods, deployments, daemonsets and statefulsets with kubesec.io
* [kubectl-ns](https://github.com/postfinance/kubectl-ns) - Simple plugin to display/switch namespaces
* [kubectl-ctx](https://github.com/postfinance/kubectl-ctx) - Simple plugin to display/switch contexts
* [kubectl-decode-secret](https://github.com/brosandilabs/kubectl-decode-secret) - Plugin to decode Kubernetes secrets 
* [kubectl-tmux-logs](https://github.com/brosandilabs/kubectl-tmux-logs) - Plugin to display container logs within separate tmux panes
* [kubectl-tmux-ssh](https://github.com/brosandilabs/kubectl-tmux-ssh) - Plugin to ssh into Kubernetes nodes within separate tmux panes
* [kubectl-kcn](https://github.com/marjamis/kubectl-kcn) - Plugin which makes it easier to ssh into nodes within your cluster
