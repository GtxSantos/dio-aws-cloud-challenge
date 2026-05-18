# Relatório de Implementação de Serviços AWS

**Data:** 18 de Maio de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Gustavo Santos de Souza  

---

## 1. Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Gustavo Santos de Souza**. O objetivo principal do projeto foi elencar 3 serviços da AWS (Amazon Web Services) com a finalidade de realizar uma diminuição de custos imediatos e otimizar a infraestrutura da empresa.

---

## 2. Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas estratégicas. A seguir, são descritos os serviços selecionados e seus respectivos casos de uso:

### Etapa 1: Armazenamento Inteligente
*   **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
*   **Foco da ferramenta:** Armazenamento de arquivos e backups com baixo custo.
*   **Descrição de caso de uso:** Migração de todos os backups físicos locais (HDs externos e fitas) e relatórios antigos da empresa para o Amazon S3. Utilizando as políticas de ciclo de vida do S3, os arquivos antigos são movidos automaticamente para a classe *S3 Glacier*, reduzindo o custo de armazenamento em mais de 70% em comparação com servidores locais.

### Etapa 2: Governança Financeira
*   **Nome da ferramenta:** AWS Budgets
*   **Foco da ferramenta:** Controle financeiro e alertas de faturamento.
*   **Descrição de caso de uso:** Configuração de um teto de gastos mensal para a infraestrutura da nuvem. O serviço envia alertas automáticos por e-mail para a gerência caso o consumo de serviços como instâncias EC2 ou bancos de dados chegue a 80% do valor estipulado, evitando surpresas ou cobranças indevidas no fim do mês.

### Etapa 3: Banco de Dados Gerenciado
*   **Nome da ferramenta:** Amazon RDS (Relational Database Service)
*   **Foco da ferramenta:** Banco de dados relacional gerenciado (MySQL/PostgreSQL).
*   **Descrição de caso de uso:** Migração dos bancos de dados que rodavam em servidores próprios para o RDS. Como a AWS cuida da manutenção, atualizações de segurança (patches) e backups automatizados, a empresa reduz o custo operacional com equipe de infraestrutura e evita gastos com perda de dados graças ao sistema de failover (Multi-AZ).

---

## 3. Conclusão
A implementação das ferramentas AWS na empresa **Abstergo Industries** trará como benefício direto a centralização dos dados, maior segurança contra perda de informações e um controle previsível do orçamento da nuvem, aumentando significativamente a eficiência e a produtividade. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca constante por novas tecnologias de otimização.

---

## 4. Anexos
*   Documentação oficial da AWS para configuração de alertas no AWS Budgets.
*   Tabela de preços comparativa entre armazenamento local vs. Amazon S3 Glacier.

---

**Assinatura do Responsável pelo Projeto:**  
*Gustavo Santos de Souza*
