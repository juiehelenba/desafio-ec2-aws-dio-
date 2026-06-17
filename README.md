# Gerenciando Instâncias EC2 na AWS

## Descrição

Este repositório foi criado como parte do desafio **Gerenciando Instâncias EC2 na AWS**, proposto pela DIO. O objetivo é documentar os conhecimentos adquiridos durante o laboratório, servindo como material de consulta para estudos futuros sobre computação em nuvem utilizando os serviços da Amazon Web Services (AWS).

## Objetivos de Aprendizagem

* Compreender o funcionamento do Amazon EC2;
* Aprender a criar e gerenciar instâncias EC2;
* Entender o conceito e a utilização de AMIs (Amazon Machine Images);
* Conhecer o processo de criação e utilização de Snapshots EBS;
* Utilizar o GitHub para documentar e compartilhar conhecimento técnico.

## O que é Amazon EC2?

O **Amazon Elastic Compute Cloud (EC2)** é um serviço da AWS que permite criar e gerenciar servidores virtuais na nuvem.

Com o Amazon EC2 é possível:

* Hospedar aplicações web;
* Executar sistemas corporativos;
* Criar ambientes de desenvolvimento e testes;
* Escalar recursos computacionais conforme a demanda;
* Reduzir custos com infraestrutura física.

## Criação de uma Instância EC2

Durante o laboratório foram abordadas as etapas necessárias para criação de uma instância EC2:

1. Acesso ao Console da AWS;
2. Navegação até o serviço Amazon EC2;
3. Criação de uma nova instância;
4. Seleção de uma Amazon Machine Image (AMI);
5. Escolha do tipo de instância;
6. Configuração de armazenamento;
7. Configuração de acesso e segurança;
8. Inicialização da instância.

## AMI (Amazon Machine Image)

Uma **AMI (Amazon Machine Image)** é uma imagem utilizada como modelo para criação de instâncias EC2.

Ela pode conter:

* Sistema operacional;
* Configurações de software;
* Aplicações instaladas;
* Configurações de inicialização;
* Bibliotecas e dependências necessárias para execução da aplicação.

### Benefícios das AMIs

* Padronização de ambientes;
* Agilidade na criação de novas instâncias;
* Facilidade de replicação de servidores;
* Redução do tempo de configuração.

## Snapshot EBS

Um **Snapshot EBS** é uma cópia de segurança (backup) de um volume Amazon EBS.

Os snapshots são utilizados para:

* Backup de dados;
* Recuperação em caso de falhas;
* Criação de novos volumes;
* Migração de ambientes;
* Proteção contra perda de dados.

### Processo de Criação de Snapshot

1. Selecionar o volume EBS desejado;
2. Criar um Snapshot;
3. Armazenar o Snapshot de forma segura na infraestrutura da AWS;
4. Restaurar os dados quando necessário.

## Aprendizados

Durante a realização deste laboratório, foi possível compreender a importância do Amazon EC2 como serviço de computação em nuvem da AWS.

Também foram estudados os conceitos de AMI, que permitem criar instâncias padronizadas de forma rápida, e de Snapshot EBS, que auxiliam na proteção e recuperação de dados.

Além dos conceitos técnicos, o desafio reforçou a importância da documentação utilizando GitHub como ferramenta de compartilhamento de conhecimento e registro de aprendizado.

## Evidências

A imagem abaixo corresponde ao desafio proposto pela DIO.

![Desafio EC2](images/DESAFIO.jgp)

## Conclusão

Este desafio permitiu consolidar conhecimentos fundamentais sobre gerenciamento de instâncias EC2, utilização de AMIs e criação de Snapshots EBS.

A prática demonstrou como a AWS oferece recursos flexíveis para provisionamento de servidores, armazenamento e recuperação de dados, contribuindo para a construção de ambientes escaláveis, seguros e de alta disponibilidade.
