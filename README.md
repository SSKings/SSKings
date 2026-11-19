# Olá, eu sou o Sérgio 👋

Desenvolvedor **Java / Spring Boot** com foco em back-end, evoluindo para full-stack com **React + TypeScript**.
Estudo programação desde 2021 e uso projetos pessoais para praticar o que se espera em produção: testes
automatizados, segurança, CI, observabilidade e deploy com Docker.

🎯 Buscando minha primeira oportunidade como **desenvolvedor back-end júnior**.

---

## ⭐ Projetos em destaque

### [ShopEasy](https://github.com/SSKings/shopeasy)

E-commerce full-stack com **API REST em Spring Boot** e **SPA em React + TypeScript**: catálogo, carrinho,
checkout com **Pix**, área do cliente e painel administrativo.

- **806 testes** com cobertura exigida no build (back-end 98% de linhas, front-end 99%) e CI com verificação de CVEs
- **6 rodadas de revisão de segurança**, cada correção com um teste que falha no código anterior: JWT com revogação,
  MFA (TOTP) para admin, bloqueio contra força bruta, rate limit, CSP/HSTS e auditoria —
  [relatório](https://github.com/SSKings/shopeasy/blob/main/docs/security-review.md)
- **Pix** com BR Code gerado no servidor e webhook com HMAC; checkout atômico, sem venda acima do estoque
- **Observabilidade com OpenTelemetry**: do clique no front até o SQL no Grafana (traces, logs e métricas) e alertas
  no Telegram
- **Pilha de produção com Docker**: PostgreSQL, API sem root, nginx com TLS e backup cifrado; capacidade medida com
  k6 (~400 ações/s dentro do SLO)
- **CI que barra regressões**: sobe a pilha de produção por cima da versão anterior com dados, scan de imagens
  (Trivy), CodeQL e teste de mutação — a `main` só aceita PR com tudo verde
- Migrado para **Spring Boot 4.1**; decisões registradas em [28 ADRs](https://github.com/SSKings/shopeasy/blob/main/docs/adr.md)

`Java 17` `Spring Boot 4.1` `Spring Security` `JPA` `Flyway` `PostgreSQL` `React 19` `TypeScript` `Tailwind`
`Docker` `nginx` `OpenTelemetry` `Grafana` `k6`

### [Bolso](https://github.com/SSKings/bolso-gestor-financeiro)

Finanças pessoais **e compartilhadas**, feitas para o dia a dia no celular: divida as contas da casa com quem mora com
você e saiba, a qualquer momento, quanto entrou, quanto saiu e quanto vai sobrar no fim do mês.

- **Espaços compartilhados** com convite; **cartão de crédito** com fatura, parcelas e pagamento; **contas fixas**,
  orçamento por categoria e **previsão do saldo** do mês
- **Importação de extrato** (OFX/CSV) sem duplicar lançamentos e **bot no Telegram**: mande `32,50 almoço` e o gasto
  entra já categorizado
- **289 testes** escritos com TDD (back-end contra PostgreSQL real, com Testcontainers) e **teste de mutação** (PIT, 95%)
- **CI que barra regressões**: contrato da API (OpenAPI gerando os tipos do front), pilha de produção subindo por cima
  da versão anterior com dados, scan de imagens (Trivy) e CodeQL — a `main` só aceita PR com tudo verde
- Segurança testada desde o começo: isolamento entre espaços também no banco, tokens revogáveis, bot que age com as
  permissões da própria pessoa — [controles e testes](https://github.com/SSKings/bolso-gestor-financeiro/blob/main/docs/security.md)
- Migrado para **Spring Boot 4.1** (Spring 7, Jackson 3) quando a linha 3.5 saiu do suporte;
  [16 ADRs](https://github.com/SSKings/bolso-gestor-financeiro/blob/main/docs/adr.md)

`Java 17` `Spring Boot 4.1` `Spring Security` `JPA` `Flyway` `PostgreSQL` `Testcontainers` `React 19` `TypeScript`
`PWA` `Docker` `nginx` `GitHub Actions` `Telegram Bot API`

## 📂 Outros projetos

| Projeto | Sobre |
|---|---|
| [MICROSERVICES](https://github.com/SSKings/MICROSERVICES) | Microsserviços com Spring Cloud: Eureka (service discovery) e Spring Cloud Gateway |
| [spring-ai-labs](https://github.com/SSKings/spring-ai-labs) | Spring AI + OpenAI: chat, geração de imagens, transcrição de áudio (Whisper) e síntese de voz |
| [spring-estudos](https://github.com/SSKings/spring-estudos) | Estudos de Spring Boot: MVC com Thymeleaf e autenticação com Spring Security |
| [K8s---KUBERNETES](https://github.com/SSKings/K8s---KUBERNETES) | Estudos de Kubernetes: manifests e comandos |

## 🛠️ Tecnologias

- **Back-end:** Java · Spring Boot · Spring Security · Spring Data JPA / Hibernate · APIs REST · OpenAPI · JWT
- **Front-end:** React · TypeScript · JavaScript · Tailwind CSS · HTML · CSS
- **Bancos de dados:** PostgreSQL · MySQL · H2 · MongoDB · Flyway
- **Testes e qualidade:** JUnit · Mockito · Testcontainers · Vitest · Testing Library · JaCoCo · PIT (mutação) · k6
- **Infra e DevOps:** Docker · nginx · GitHub Actions · Trivy · CodeQL · Dependabot · Linux · Git · Kubernetes (estudos)
- **Observabilidade:** OpenTelemetry · Grafana · Prometheus · Loki · Tempo
- **Outras linguagens:** Python · C · Rust

## 📚 Estudando agora

Arquitetura de software · Microsserviços · Kubernetes

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/sskings) · [Site](https://sskings.github.io)
