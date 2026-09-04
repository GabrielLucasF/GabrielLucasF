# Gabriel Lucas Ferreira dos Santos

**Desenvolvedor Backend — PHP e Laravel.** Trabalho com sistemas que movimentam dinheiro: pagamentos, marketplace e logística.

Há 2 anos na [Braip](https://braip.com), numa plataforma composta por um monolito Laravel com 51 contribuidores e mais de 20 microsserviços. Contribuí de forma relevante em 10 serviços de backend e sou o maior contribuidor individual de dois deles.

O problema que eu mais resolvo: **consistência de estado quando algo dá errado.** Quando o gateway de pagamento dá timeout, quando o webhook chega duas vezes, quando um serviço confirma e o outro não escuta — é aí que dinheiro some da contabilidade. Encontrar e fechar essas divergências é boa parte do meu trabalho.

---

### Stack

**Principal**
`PHP` `Laravel 10/11` `MySQL` `REST APIs` `PHPUnit`

**Mensageria e dados**
`RabbitMQ` `Redis` `PostgreSQL`

**Infra**
`Docker` `Kubernetes (AWS EKS/ECR)` `ArgoCD` `CI/CD` `Sentry`

**Complementar**
`Go` `Vue` `Node.js`

**Arquitetura**
`Microsserviços` `Event-driven` `Arquitetura hexagonal` `Design patterns` `Anti-corruption layers`

**Domínio**
`Pagamentos` `Estornos e chargebacks` `Conciliação financeira` `Webhooks e postbacks` `NF-e` `Integração com ERP e transportadoras`

---

### O que construí

**Backend de logística e fulfillment** — Laravel 10
Maior contribuidor individual: 996 de 2.480 commits (40%), presente desde a primeira semana do projeto. 31 domínios de negócio — motor de frete, emissão de NF-e, pagamento na entrega, rastreio e conciliação financeira — com testes unitários e de integração.

**Microsserviço de estornos e chargebacks** — Laravel 11
Principal autor: 233 de 497 commits (47%), o maior contribuidor entre 18 pessoas. Arquitetura event-driven sobre RabbitMQ, autenticação JWT entre serviços e deploy em Kubernetes.

**Performance**
Reduzi o export de um relatório de vendas de mais de 5 minutos para cerca de 1,4 segundo, corrigindo o plano de execução da consulta no MySQL.

**Resiliência**
Padronizei o tratamento de falhas de terceiros em quatro integrações diferentes — pagamentos, Correios, consulta de CEP e Mautic. Mesmo padrão em todas: classificação 4xx contra 5xx, timeout, retry com backoff e circuit breaker.

**Go**
163 commits e 25 pull requests em cinco microsserviços, em arquitetura hexagonal.

> Esse trabalho está em repositórios privados. Os projetos públicos abaixo mostram as mesmas ideias em escala menor.

---

### Formação

**Análise e Desenvolvimento de Sistemas** (tecnólogo) · [Uninter](https://www.uninter.com), EAD
Em andamento, com conclusão prevista para 2028.

---

### Contato

[LinkedIn](https://www.linkedin.com/in/gabriellucasf-dev/) · [Email](mailto:gabriel.fersants@gmail.com)
