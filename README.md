# Atividade 4 - # Infrastructure and Cloud Architecture

Subir dois pods, nginx e mysql, mapeando a porta 80 do nginx para acesso externo ao cluster e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql pela porta 3306. 

# Pré-requisito

- Instalar kubectl
- Instalar mikube


# Passo à Passo para a execução do script
- 1 - Executar comandos abaixo
 > kubectl apply -f k8s-nginx.yml
 
 > kubectl apply -f k8s-data-base.yml
 
# Evidências
![PODS](https://i.imgur.com/M8CA6lS.jpeg)

![Ingress](https://i.imgur.com/y7LlEpc.jpeg)


## Grupo A - Integrantes
- Alessandra Souza da Silva
- Elizangela Fernandes Leal
- Henrique Araújo Rosa
- Mariana Silva Dutra
- Rafael da Silva Muni
- Vinicius Moreira da Silva
