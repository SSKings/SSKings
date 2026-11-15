# Olá, eu sou o Sérgio 👋

Desenvolvedor **Java / Spring Boot** com foco em back-end, evoluindo para full-stack com **React + TypeScript**.
Estudo programação desde 2021 e uso projetos pessoais para praticar o que se espera em produção: testes
automatizados, segurança, CI, observabilidade e deploy com Docker.

🎯 Buscando minha primeira oportunidade como **desenvolvedor back-end júnior**.

---

## ⭐ Projeto em destaque: [ShopEasy](https://github.com/SSKings/shopeasy)

E-commerce full-stack com **API REST em Spring Boot** e **SPA em React + TypeScript**: catálogo, carrinho,
checkout com **Pix**, área do cliente e painel administrativo.

- **785 testes** com cobertura exigida no build (back-end 98% de linhas, front-end 99%) e CI com verificação de CVEs
- **6 rodadas de revisão de segurança**, cada correção com um teste que falha no código anterior: JWT com revogação,
  MFA (TOTP) para admin, bloqueio contra força bruta, rate limit, CSP/HSTS e auditoria —
  [relatório](https://github.com/SSKings/shopeasy/blob/main/docs/security-review.md)
- **Pix** com BR Code gerado no servidor e webhook com HMAC; checkout atômico, sem venda acima do estoque
- **Observabilidade com OpenTelemetry**: do clique no front até o SQL no Grafana (traces, logs e métricas) e alertas
  no Telegram
- **Pilha de produção com Docker**: PostgreSQL, API sem root, nginx com TLS e backup cifrado; capacidade medida com
  k6 (~400 ações/s dentro do SLO)
- Decisões registradas em [26 ADRs](https://github.com/SSKings/shopeasy/blob/main/docs/adr.md)

`Java 17` `Spring Boot 3.5` `Spring Security` `JPA` `Flyway` `PostgreSQL` `React 19` `TypeScript` `Tailwind`
`Docker` `nginx` `OpenTelemetry` `Grafana` `k6`

## 📂 Outros projetos

| Projeto | Sobre |
|---|---|
| [gestor-financeiro](https://github.com/SSKings/gestor-financeiro) | API REST de finanças pessoais: contas, cartões e lançamentos, com Spring Security + JWT, PostgreSQL e Docker |
| [MICROSERVICES](https://github.com/SSKings/MICROSERVICES) | Microsserviços com Spring Cloud: Eureka (service discovery) e Spring Cloud Gateway |
| [spring-ai-labs](https://github.com/SSKings/spring-ai-labs) | Spring AI + OpenAI: chat, geração de imagens, transcrição de áudio (Whisper) e síntese de voz |
| [spring-estudos](https://github.com/SSKings/spring-estudos) | Estudos de Spring Boot: MVC com Thymeleaf e autenticação com Spring Security |
| [K8s---KUBERNETES](https://github.com/SSKings/K8s---KUBERNETES) | Estudos de Kubernetes: manifests e comandos |

## 🛠️ Tecnologias

- **Back-end:** Java · Spring Boot · Spring Security · Spring Data JPA / Hibernate · APIs REST · JWT
- **Front-end:** React · TypeScript · JavaScript · Tailwind CSS · HTML · CSS
- **Bancos de dados:** PostgreSQL · MySQL · H2 · MongoDB · Flyway
- **Testes e qualidade:** JUnit 5 · Mockito · Vitest · Testing Library · JaCoCo · k6
- **Infra e DevOps:** Docker · nginx · GitHub Actions · Linux · Git · Kubernetes (estudos)
- **Observabilidade:** OpenTelemetry · Grafana · Prometheus · Loki · Tempo
- **Outras linguagens:** Python · C · Rust

## 📚 Estudando agora

Arquitetura de software · Microsserviços · Kubernetes

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/sskings) · [Site](https://sskings.github.io)
