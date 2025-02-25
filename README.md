# Estrutura do Projeto e Descrição do Dashboard

## Estrutura do Projeto

Este projeto consiste na criação de um dashboard interativo para análise de vendas de assinaturas do Xbox Game Pass e pacotes de temporada relacionados.
A estrutura do projeto segue os seguintes componentes:

### 1. Base de Dados

A fonte de dados contém informações sobre assinantes, planos, preços e detalhes de cada assinatura.

**Campos principais da base de dados:**

* `Subscriber ID`: Identificação única do assinante.
* `Name`: Nome do assinante.
* `Plan`: Tipo de plano assinado.
* `Start Date`: Data de início da assinatura.
* `Auto Renewal`: Indica se a renovação automática está ativada.
* `Subscription Price`: Valor da assinatura.
* `Subscription Type`: Tipo de assinatura (Anual, Mensal, Trimestral).
* `EA Play Season Pass`: Indica se o assinante possui o passe da EA Play.
* `EA Play Season Pass Price`: Preço do passe da EA Play.
* `Minecraft Season Pass`: Indica se o assinante possui o passe da Minecraft.
* `Minecraft Season Pass Price`: Preço do passe da Minecraft.
* `Coupon Value`: Valor de desconto aplicado.
* `Total Value`: Valor total pago pelo assinante.

### 2. Dashboard

O dashboard foi desenvolvido para exibir de forma visual e interativa os dados de assinaturas, com os seguintes componentes:

* **Cabeçalho:**
    * Nome do projeto: XBOX GAME PASS SUBSCRIPTIONS SALES.
    * Período de cálculo: 01/01/2024 - 31/12/2024.
    * Data de atualização dos dados: 25/12/2024 09:00:00.
* **Seção de Assinaturas de Pacotes de Temporada:**
    * TOTAL SUBSCRIPTIONS EA PLAY SEASON PASS: Valor total arrecadado com assinaturas do EA Play Season Pass (R$ 990,00).
    * TOTAL SUBSCRIPTIONS MINECRAFT SEASON PASS: Valor total arrecadado com assinaturas do Minecraft Season Pass (R$ 1.140,00).
* **Gráfico de Assinaturas do Xbox Game Pass:**
    * Exibe a quantidade de assinaturas ativas (Yes - R$ 747,00) e inativas (No - R$ 2.824,00).
* **Painel de Filtros:**
    * O usuário pode selecionar entre os tipos de assinatura: Anual, Mensal, Trimestral.
    * Filtro de assinaturas baseado na escolha do usuário.

### 3. Objetivo do Projeto

O objetivo principal é facilitar a análise das assinaturas do Xbox Game Pass e pacotes de temporada, permitindo visualizar a distribuição de usuários, 
valores arrecadados e proporções entre os diferentes planos. A interface foi projetada para ser intuitiva e fornecer informações relevantes rapidamente.

### 4. Fonte do Projeto

Este projeto foi desenvolvido com base no curso "Criando um Dashboard de Vendas do Xbox com Excel" da plataforma educacional DIO, ministrado pelo Tech Educator Felipe Aguiar. 
Eu apenas inserir algumas perguntas de negócio para enriquer o projeto. O dashboard, a base de dados e alguns cálculos são de autoria da própria plataforma e do respectivo professor.

Este `README.md` descreve apenas a estrutura do projeto e a organização do dashboard. Para detalhes técnicos específicos, consulte a documentação de implementação do código.
