```
apt install htop curl dstat iotop
apt install xfce4 xfce4-goodies
helm install grafana grafana/grafana -f grafana-values.yaml
helm install vm-server vm/victoria-metrics-single
helm install vault hashicorp/vault -f vault-values.yaml
helm install vm-agent vm/victoria-metrics-agent -f vm-agent.yaml
```
