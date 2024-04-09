Reproducing the issue:
- replace {{DOMAIN}} with public wildcard URL
- kubectl apply -f genesis.cm.yaml
- kubectl apply -f node1.yaml
- wait until pod starts
- kubectl apply -f node2.yaml
- check node1 logs
