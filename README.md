### Criação simples de um cluster k8s com kind
No arquivo kind/kind.yaml temos a configuração de 4 nodes, onde NÃO estamos mapeando nenhum volume, caso queira mapear algum volume, apenas descomente as linhas comentadas

### Subir cluster
```
kind create cluster --config kind/kind.yaml --name k8s
```