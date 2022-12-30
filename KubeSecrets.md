* To encode a string using base64: echo -n "{your desired string}" | base64
* To decode a base64 string into plain text: echo -n "{encoded string}" | base64 --decode


[please follow the document provided by Suse about the namespaces](https://www.suse.com/c/rancher_blog/introduction-to-kubernetes-namespaces/)
* To switch to a different namespace: kubectl config set-context $(kubectl config current-context) --namespace={desired namespace}

* ps aux : command is a tool to monitor processes running on your Linux system.
* [decode a token](https://jwt.io/)

* To extract logs from a pods: kubectl -n <name-space> exec -it <podname> -- cat {path of the logs}/log/app.log
