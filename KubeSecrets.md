* To encode a string using base64: echo -n "{your desired string}" | base64
* To decode a base64 string into plain text: echo -n "{encoded string}" | base64 --decode
* To switch to a different namespace: kubectl config set-context $(kubectl config current-context) --namespace={desired namespace}
