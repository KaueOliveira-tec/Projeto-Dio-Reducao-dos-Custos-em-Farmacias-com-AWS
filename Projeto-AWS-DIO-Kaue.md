# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 16/08/2025
Empresa: Abstergo Industries 
Responsável: Kauê de Oliveira Martins

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Kauê de Oliveira Martins. 
O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Nome da ferramenta: AWS Cost Explorer
- Foco da ferramenta: Visualização e análise detalhada dos custos para identificar oportunidades de economia
= Descrição de caso de uso: Implementação de dashboards personalizados para monitorar gastos por serviço, região e tags. Identificação de recursos ociosos (instâncias EC2 e volumes EBS não utilizados) e recomendações de reservas e Savings Plans com base no histórico de uso. Previsão de gastos futuros para melhor planejamento orçamentário.

Etapa 2: 
- Nome da ferramenta: AWS Auto Scaling
- Foco da ferramenta: Dimensionamento automático de recursos conforme demanda real
- Descrição de caso de uso: Configuração de políticas de escalonamento para grupos de EC2 baseadas em métricas de CPU, memória ou rede. Implementação de escalonamento horizontal para aplicações com grande importância, garantindo desempenho durante picos de demanda e reduzindo custos automaticamente durante períodos de baixa utilização.

Etapa 3: 
- Nome da ferramenta: Amazon S3 Intelligent-Tiering
- Foco da ferramenta: Redução automática de custos de armazenamento baseada em padrões de acesso
- Descrição de caso de uso: Migração de dados do S3 Standard para Intelligent-Tiering para armazenamento que move automaticamente objetos entre níveis frequente, infrequente e de arquivo conforme padrões de acesso. Implementação de políticas de ciclo de vida para dados com padrões de acesso conhecidos. Redução de até 70% nos custos de armazenamento sem impacto na disponibilidade dos dados.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado redução imediata de custos operacionais em até 40%, otimização automática de recursos computacionais e de armazenamento, além de maior visibilidade e controle sobre os gastos em nuvem, o que aumentará a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[AWS Cost Explorer](https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/)

[AWS Cost Explorer - Documentação](https://docs.aws.amazon.com/cost-management/latest/userguide/cost-explorer-what-is.html)

[AWS Auto Scaling](https://aws.amazon.com/autoscaling/)

[AWS Auto Scaling - Documentação](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)

[AWS Auto Scaling - Guia de boas práticas](https://aws.amazon.com/blogs/infrastructure-and-automation/best-practices-for-aws-auto-scaling/)

[Amazon S3 Intelligent-Tiering](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/)

[Amazon S3 Intelligent-Tiering - Documentação](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html)



Assinatura do Responsável pelo Projeto:

Kauê de Oliveira Martins
