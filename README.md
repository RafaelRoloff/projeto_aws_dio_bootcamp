# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 11/01/2026
Empresa: **Abstergo Industries**
Responsável: **Rafael Roloff**

---

## Introdução

Este relatório apresenta o processo de planejamento para implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **Rafael Roloff**. O objetivo do projeto é apresentar **3 serviços da AWS** que possam ser adotados pela empresa com foco principal na **redução de custos operacionais**, além de ganhos em escalabilidade, segurança e eficiência.

A Abstergo, atuando no setor farmacêutico e ainda sem infraestrutura em nuvem, pode se beneficiar do modelo *pay-as-you-go* da AWS, evitando altos investimentos iniciais em servidores físicos, manutenção e licenças.

---

## Descrição do Projeto

O projeto foi dividido em **3 etapas**, cada uma representando a adoção de um serviço AWS estratégico para redução de custos e modernização da infraestrutura.

### Etapa 1:

* **Nome da ferramenta:** Amazon EC2
* **Foco da ferramenta:** Computação sob demanda
* **Descrição do caso de uso:**
  O Amazon EC2 permitirá que a Abstergo execute seus sistemas internos (como ERP, sistemas de pedidos e relatórios) em servidores virtuais, pagando apenas pelo tempo de uso. Isso elimina a necessidade de compra e manutenção de servidores físicos, reduzindo custos iniciais e permitindo escalar os recursos conforme a demanda do negócio.

**Principais ganhos:**

* Redução de CAPEX (investimento em hardware)
* Escalabilidade automática conforme o volume de acessos
* Pagamento apenas pelo uso

---

### Etapa 2:

* **Nome da ferramenta:** Amazon S3
* **Foco da ferramenta:** Armazenamento de objetos
* **Descrição do caso de uso:**
  O Amazon S3 será utilizado para armazenar documentos corporativos, relatórios, backups e arquivos relacionados a pedidos e distribuição de medicamentos. Por ser altamente durável e de baixo custo, o S3 substitui servidores locais de arquivos e soluções de armazenamento tradicionais.

**Principais ganhos:**

* Custo reduzido para grandes volumes de dados
* Alta durabilidade e disponibilidade
* Possibilidade de uso de classes mais baratas (como Glacier) para dados antigos

---

### Etapa 3:

* **Nome da ferramenta:** Amazon RDS
* **Foco da ferramenta:** Banco de dados relacional gerenciado
* **Descrição do caso de uso:**
  O Amazon RDS permitirá hospedar bancos de dados relacionais (como MySQL ou PostgreSQL) sem a necessidade de gerenciar infraestrutura, backups ou atualizações manuais. Isso reduz custos operacionais e diminui a necessidade de uma equipe dedicada exclusivamente à administração de bancos de dados.

**Principais ganhos:**

* Backups automáticos e patches gerenciados
* Alta disponibilidade com opção Multi-AZ
* Redução de custos com administração e manutenção

---

## Conclusão

A implementação dos serviços **Amazon EC2, Amazon S3 e Amazon RDS** na empresa **Abstergo Industries** tem como objetivo principal a **redução de custos operacionais**, aliada ao aumento da **eficiência, segurança e escalabilidade** da infraestrutura de TI.

Com a adoção da nuvem AWS, a empresa evita grandes investimentos iniciais, paga apenas pelo que consome e ganha flexibilidade para crescer conforme a demanda do mercado farmacêutico. Recomenda-se a continuidade da adoção de soluções em nuvem e a avaliação futura de novos serviços AWS para otimização adicional dos processos.

---

## Anexos

* Documentação oficial da AWS:
https://docs.aws.amazon.com/ec2/
https://docs.aws.amazon.com/s3/
https://docs.aws.amazon.com/rds/
https://aws.amazon.com/pricing/
https://docs.aws.amazon.com/wellarchitected/
* Planilha comparativa de custos (on-premises vs cloud)

---

Assinatura do Responsável pelo Projeto:

**Rafael Roloff**
