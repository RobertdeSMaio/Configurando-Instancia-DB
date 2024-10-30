# Configurando-Instancia-DB

Esta guia explica como configurar uma instância de banco de dados no Microsoft Azure.

## Introdução

O Microsoft Azure oferece uma variedade de opções de banco de dados, como o SQL Database, MySQL, PostgreSQL e Cosmos DB. Este guia se concentra na criação e configuração de uma instância de banco de dados relacional.

Acesse o portal do Azure: Visite https://portal.azure.com.


## Criando uma Instância de Banco de Dados

### Passo 1: Acessar a Seção de Banco de Dados

No menu à esquerda, clique em "Todos os Serviços", no campo de busca, digite "Banco de Dados" e selecione o tipo de banco de dados desejado (por exemplo, "SQL Database", "MySQL", "PostgreSQL"), clique em "Adicionar" ou "Criar" para iniciar o processo de criação de uma nova instância de banco de dados.

### Passo 2: Configurações Básicas

Assinatura e Grupo de Recursos: Escolha a assinatura correta e selecione ou crie um grupo de recursos.

Nome do Banco de Dados: Insira um nome único para a instância do banco de dados.

Servidor e Localização: Selecione ou crie um novo servidor de banco de dados e escolha a localização (região) onde ele será hospedado.

Versão do Banco de Dados: Escolha a versão do banco de dados (ex.: SQL Server, MySQL 5.7, PostgreSQL 12).

### Passo 3: Configurações de Escalabilidade

Camada de Serviço: Selecione a camada de serviço mais adequada, como Basic, Standard, ou Premium, dependendo das suas necessidades de desempenho e custo.

Tamanho e Desempenho: Ajuste o número de DTUs ou vCores, conforme necessário, para determinar o desempenho da instância.

### Passo 4: Configurações de Segurança

Autenticação: Configure a autenticação do banco de dados. Você pode optar por usar autenticação por senha ou integração com o Active Directory.

Firewall: Defina as regras de firewall para controlar quais endereços IP podem acessar o banco de dados.

Backup e Recuperação: Configure as opções de backup, incluindo backups automáticos e retenção de backups.

### Passo 5: Revisão e Criação

Revisar Configurações: Revise todas as configurações inseridas e ajuste conforme necessário.

Implantação: Clique em "Criar" para iniciar o processo de criação da instância de banco de dados. A criação pode levar alguns minutos, gerenciando a Instância de Banco de Dados

Acessar o Banco de Dados: Após a criação, você pode acessar o banco de dados usando ferramentas como o SQL Server Management Studio (SSMS) ou MySQL Workbench, dependendo do tipo de banco de dados.

Configurações Adicionais: No painel da instância de banco de dados no Azure, você pode ajustar o desempenho, realizar backups, restaurar o banco de dados, e monitorar o uso de recursos.
