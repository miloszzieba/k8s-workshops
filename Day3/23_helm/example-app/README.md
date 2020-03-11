https://helm.sh/docs/intro/install/

wget https://get.helm.sh/helm-v3.1.1-linux-amd64.tar.gz
tar -zxvf helm-v3.1.1-linux-amd64.tar.gz
sudo mv linux-amd64/helm /usr/local/bin/helm

```sh
helm template --output-dir=./output .
helm template --output-dir=./output --values .\production.values.yaml .
```