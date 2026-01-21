# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 21 de janeiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Eduardo Oliveira

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado para otimização de infraestrutura em nuvem. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e melhorar a eficiência operacional.

A implementação seguiu uma metodologia estruturada em etapas, permitindo avaliação cuidadosa de cada solução antes de sua adoção em ambiente de produção.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização Amazon EC2

O Amazon EC2 será utilizado com ênfase em dimensionamento correto de instâncias. Máquinas superdimensionadas serão identificadas para aplicação de Auto Scaling e Reserved Instances, com projeção de redução de 35-40% nos custos computacionais no primeiro ano.

### Etapa 2: Armazenamento Inteligente S3

O Amazon S3 Intelligent Tiering será implementado para gestão automática de dados por frequência de acesso. Dados pouco utilizados migrarão para camadas econômicas como Glacier, com economia projetada de até 60% em armazenamento de arquivos históricos.

### Etapa 3: Processamento Serverless Lambda

O AWS Lambda substituirá tarefas de ETL e processamento de logs em instâncias sempre ativas. A cobrança por tempo de execução real prevê redução de até 90% em custos específicos, como de R$2.000 para R$200 mensais.

## Resultados Esperados

A implementação destes três serviços AWS na empresa Abstergo Industries tem como esperado:

- **Redução de custos:** Diminuição estimada de 50-60% nos gastos com infraestrutura em nuvem
- **Aumento de escalabilidade:** Capacidade automática de escalar recursos conforme demanda
- **Melhor utilização de recursos:** Eliminação de ociosidade através de provisionamento inteligente
- **Redução de carga operacional:** Menos tempo dedicado a manutenção de servidores

Estes benefícios aumentarão significativamente a eficiência e a produtividade da empresa, liberando recursos internos para projetos de maior valor agregado.

## Conclusão

A implementação de ferramentas AWS na empresa Abstergo Industries tem como esperado a redução de custos operacionais, aumento de escalabilidade e melhoria na utilização de recursos computacionais, o que aumentará a eficiência e a produtividade da empresa. 

Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa. Adicionalmente, sugere-se:

- Implementação de AWS Cost Explorer para monitoramento contínuo de gastos
- Adoção de AWS Trusted Advisor para otimizações adicionais
- Revisão trimestral da arquitetura para identificar novas oportunidades de economia

## Anexos

- [Manual de configuração do Auto Scaling em EC2](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- [Documentação de políticas de Intelligent Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering-overview.html)
- [Guia de desenvolvimento com AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/getting-started.html)
- [Relatório de análise de custos anterior e posterior à implementação](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html)
- [AWS Savings Plans para Reserved Instances](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html)



**Assinatura do Responsável pelo Projeto:**


Eduardo Oliveira
