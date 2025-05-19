# 💻 Benefícios da Computação em Nuvem – Laboratório

Este repositório apresenta os principais benefícios da computação em nuvem, com base nos recursos e boas práticas da Microsoft Azure.

---

## ✅ Alta Disponibilidade

A Microsoft garante altos níveis de disponibilidade por meio de SLAs (Service Level Agreements), com percentuais como:

- 99%
- 99,9%
- 99,95%

Com base nesses valores, é possível estimar o tempo máximo de indisponibilidade de cada serviço. Se o serviço não atender ao SLA acordado, a Microsoft concede créditos proporcionais ao valor do serviço afetado.

> Quando um serviço está fora do ar ou apresenta falhas, ele é considerado degradado.

Todas as condições do SLA se aplicam igualmente a todos os usuários.

---

## 📈 Escalabilidade e Elasticidade

### 🔼 Escalabilidade

A escalabilidade é a capacidade de aumentar ou diminuir os recursos conforme a demanda.  
Exemplo: se um aplicativo precisar de mais processamento, ele pode escalar verticalmente, adicionando mais CPU ou memória à máquina virtual.

### 🔁 Elasticidade

A elasticidade permite expandir os recursos automaticamente ou manualmente diante de variações bruscas de uso.

- Exemplo: durante eventos como a Black Friday, os recursos podem ser expandidos para suportar o aumento de acessos.
- Você pode definir gatilhos para adicionar ou remover recursos com base na utilização (ex: uso de GPU acima de 75%).

📌 Paga-se apenas pelos recursos utilizados, e é possível definir limites mínimos e máximos para alocação automática.

---

## 🔒 Confiabilidade, Previsibilidade e Segurança

### ✅ Confiabilidade

- A nuvem é resiliente: mesmo com falhas, os serviços continuam funcionando.
- Arquitetura distribuída permite replicação de recursos em diferentes regiões do mundo, garantindo continuidade mesmo diante de desastres.

### 📊 Previsibilidade

- Permite prever custos e desempenho com base no Azure Well-Architected Framework.
- Ajuda no planejamento e suporte contínuo às operações.

### 🔐 Segurança

- A nuvem fornece ferramentas para proteger dados e recursos.
- Algumas medidas (como atualizações de sistema) são responsabilidade do cliente.

---

## 🛡️ Governança e Gerenciamento

### ⚙️ Governança

- Permite definir padrões corporativos e monitorar a conformidade.
- Exemplo: bloquear a criação de recursos em regiões fora da estratégia da empresa.
- Quanto antes for estabelecida, mais segura e eficiente será a operação em nuvem.

### 🧩 Gerenciabilidade

- Permite escalar recursos automaticamente de acordo com a demanda.
- Implantação facilitada com modelos pré-configurados (sem necessidade de configurações manuais).
- A gestão dos recursos pode ser feita via portal web, linha de comando (CLI), scripts ou APIs.

---

Feito com 💙 para fins de estudo e prática com computação em nuvem.
