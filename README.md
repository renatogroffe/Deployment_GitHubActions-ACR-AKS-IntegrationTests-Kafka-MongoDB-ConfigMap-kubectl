# Deployment_GitHubActions-ACR-AKS-IntegrationTests-Kafka-MongoDB-ConfigMap-kubectl
Workflow do GitHub Actions para execução automatizada de testes de integração (baseados em .NET 5 e no uso de Apache Kafka + MongoDB), build e deployment de uma aplicação que faz uso de containers com publicação de imagens no Azure Container Registry e deployment no AKS - Azure Kubernetes Service (inclui ainda o uso de Variables, além de um ConfigMap e do kubectl - com os comandos annotate e rollout).

Projeto que serviu de base para a construção deste workflow:
https://github.com/renatogroffe/DotNet5-WorkerService-Kafka-MongoDB-IntegrationTests_Acoes
