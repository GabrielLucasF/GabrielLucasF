# Gabriel Lucas Ferreira dos Santos
### Backend Software Engineer | PHP (Laravel) & Go (Golang) | Payment Systems, Sub-Acquiring & Logistics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gabriellucasf--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriellucasf-dev/)
[![Email](https://img.shields.io/badge/Email-gabriel.fersants%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabriel.fersants@gmail.com)
[![Location](https://img.shields.io/badge/Location-Minas_Gerais,_Brazil_(Remote_/_Hybrid)-10B981?style=for-the-badge)](https://www.linkedin.com/in/gabriellucasf-dev/)

---

### Sobre Mim / About Me

**[PT-BR]** Engenheiro de Software Backend com **+4 anos de experiência prática em tecnologia**, especializado na construção, arquitetura e sustentação de sistemas distribuídos, motores de pagamentos/subadquirência e plataformas logísticas de missão crítica em **PHP (Laravel 10/11)** e **Go (Golang)**. Atualmente atuo na engenharia da **Braip** (plataforma de pagamentos, marketplace, assinaturas e fulfillment com +20 microsserviços), onde sou o maior contribuidor individual do backend de logística e do microsserviço de estornos/chargebacks, além de implementar fluxos críticos de negócio em 5 microsserviços e bibliotecas core em Go.

**[EN]** Backend Software Engineer with **4+ years of hands-on experience in tech**, specializing in mission-critical distributed systems, payment & sub-acquiring engines, and logistics platforms using **PHP (Laravel 10/11)** and **Go (Golang)**. Currently building and scaling a high-volume payments, marketplace, and fulfillment ecosystem across a 51-contributor Laravel monolith and 20+ microservices.

---

### Impacto Técnico em Produção / Production Engineering Highlights

- **Liderança Técnica em Serviços Core (Laravel 10/11):** Maior contribuidor individual do **Backend de Logística & Fulfillment** (`Laravel 10`, **40% dos commits** — 996 de 2.480 commits em 31 domínios de negócio) e Autor Principal do **Microsserviço de Estornos & Chargebacks** (`Laravel 11`, **47% dos commits** — 233 de 497 commits entre 18 engenheiros).
- **Engenharia de Microsserviços Críticos em Go (Golang):** Desenvolvimento de funções críticas em **5 microsserviços e pacotes core em Go** (`ms-commissions`, `ms-postback-api`, `ms-metrics`, `ms-orders`, `ms-tracking` e `go-core` — **+163 commits e +25 PRs**), aplicando **Arquitetura Hexagonal (Ports & Adapters)**, **Anti-Corruption Layers (ACL)**, **GORM**, **Uber Dig (IoC)**, **GolangCI-Lint** e **SonarQube** (handlers de cancelamento/redistribuição de comissões, domínio de área de membros, APIs externas de vendas, agregação analítica de dashboards e renderização de boletos em PDF).
- **Engenharia de Pagamentos, Cascata de Crédito & Subadquirência (URs / SLC / BaaS):** Construção do motor de **compensação financeira de chargebacks** (formação de dívida, recuperação via Unidades de Recebíveis/URs e conciliação de retorno do SLC), persistência granular de tentativas da cascata de crédito, reagendamento contra *rate-limit* na Asaas, integração de subcontas HG Pagamentos e ativação de contas BaaS/BAG.
- **Performance e Otimização de Banco de Dados (MySQL & PostgreSQL):** Redução de **99,5% no tempo de exportação de relatórios críticos no MySQL** (de **+5 minutos para ~1,4 segundo**) via refatoração de plano de execução (`EXPLAIN`), além de otimização de queries analíticas em PostgreSQL/GORM.
- **Engenharia de Resiliência, Segurança & Qualidade:** Padronização de **Circuit Breaker, Retry com Exponential Backoff, Locks Distribuídos no Redis e Timeouts** em integrações HTTP (Netrin, Mautic, Bling OAuth2, Shopify Webhooks e transportadoras), correção de vulnerabilidades IDOR multi-tenant e **584 Pull Requests mergeados + 214 Code Reviews** em 2 anos.

---

### Stack Tecnológica / Tech Stack

**Linguagens & Ecossistemas Principais (Core Stack)**
![PHP](https://img.shields.io/badge/PHP_8.x-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_10%2F11-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Go](https://img.shields.io/badge/Go_(Golang)-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

**Banco de Dados, Cache & Mensageria**
![MySQL](https://img.shields.io/badge/MySQL_(Query_Tuning)-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(GORM)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_(Cache_%26_Locks)-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ_(AMQP)-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infraestrutura, DevOps, Testes & Observabilidade**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(AWS_EKS)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

### Arquitetura e Domínios que Domino / Core Engineering Domains

| Domínio | Práticas e Padrões Aplicados em Produção |
| :--- | :--- |
| **Pagamentos, Subadquirência & Comissões (PHP & Go)** | Cascata de crédito multi-adquirente (Asaas, Pagar.me, HG Pagamentos), compensação de chargebacks via Unidades de Recebíveis (URs) e conciliação SLC, abertura de contas BaaS/BAG, handlers assíncronos de comissões (`ms-commissions` em Go) e geração de boletos (`go-core/boleto`). |
| **Logística, Postbacks & Fiscal (Laravel & Go)** | Motor de cotação de frete multi-transportadora (Correios, Loggi, Jadlog, JetExpress), cálculo padronizado de cubagem, emissão de NF-e, APIs externas de vendas e postbacks (`ms-postback-api` em Go) e integração OAuth2 com ERP Bling. |
| **Resiliência, Segurança & Escala** | Circuit Breaker, Retry com Exponential Backoff, Locks distribuídos em dois estágios no Redis, Anti-Corruption Layers (ACL), Arquitetura Hexagonal em Go, isolamento multi-tenant/RBAC e mensageria via RabbitMQ. |
