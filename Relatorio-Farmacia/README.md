# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17/01/2026

Empresa: Abstergo Industries

Responsável: Julia França Iglesias

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Julia França Iglesias. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serÃ£o descritas as etapas do projeto:

---

### Etapa 1 – Amazon EC2 + Auto Scaling

* **Nome do serviço:** Amazon EC2 (Elastic Compute Cloud) com Auto Scaling
* **Foco:** Redução de custos com servidores físicos
* **Caso de uso:**

Atualmente, a empresa mantém servidores locais para sistemas internos (estoque, vendas, financeiro), que geram custos fixos elevados, independentemente do uso.

Com a migração para **Amazon EC2**, os servidores passam a ser virtuais, hospedados na nuvem, com as seguintes vantagens:

* Pagamento apenas pelo tempo de uso
* Eliminação de custos com hardware, manutenção e refrigeração
* Possibilidade de ajustar automaticamente a capacidade conforme a demanda (Auto Scaling)

**Redução de custos esperada:**

* Eliminação de investimentos em novos servidores físicos
* Redução de gastos com energia elétrica e manutenção

---

### Etapa 2 – Amazon S3 (Simple Storage Service)

* **Nome do serviço:** Amazon S3
* **Foco:** Redução de custos com armazenamento e backup
* **Caso de uso:**

A empresa mantém dados como:

* Relatórios fiscais
* Documentos contábeis
* Backups de sistemas

Esses dados podem ser armazenados no **Amazon S3**, que oferece:

* Alta durabilidade e segurança
* Custos significativamente menores em comparação a storage local
* Eliminação de fitas, HDs externos e servidores dedicados

Além disso, políticas de armazenamento permitem mover dados antigos para camadas ainda mais baratas, como o **S3 Glacier**.

**Redução de custos esperada:**

* Menor gasto com equipamentos de armazenamento
* Redução de custos com backup e recuperação de dados

---

### Etapa 3 – Amazon RDS (Relational Database Service)

* **Nome do serviço:** Amazon RDS
* **Foco:** Redução de custos e simplificação da gestão de banco de dados
* **Caso de uso:**

Atualmente, a empresa mantém bancos de dados em servidores locais, o que exige:

* Manutenção constante
* Atualizações manuais
* Custos com hardware e suporte especializado

Com o **Amazon RDS**, o banco de dados passa a ser gerenciado pela AWS, oferecendo:

* Atualizações automáticas
* Backups automáticos
* Alta disponibilidade
* Pagamento conforme uso

Isso reduz significativamente a necessidade de servidores dedicados e de intervenção técnica constante.

**Redução de custos esperada:**

* Eliminação de custos com servidores exclusivos para banco de dados
* Redução de horas de suporte técnico
* Menor risco de indisponibilidade

---

## Conclusão

A migração parcial para a AWS permite à Abstergo Industries reduzir custos de forma imediata e sustentável, ao mesmo tempo em que moderniza sua infraestrutura de TI.

Os principais benefícios esperados são:

* Redução de custos fixos com infraestrutura
* Maior controle e previsibilidade financeira
* Aumento da disponibilidade e segurança dos sistemas
* Facilidade de crescimento sem grandes investimentos

---

## Anexos

* Estimativa de custos AWS
* Comparativo On‑Premises x Cloud
* Documentação básica dos serviços AWS

---

Assinatura do Responsável pelo Projeto:
Julia França Iglesias
