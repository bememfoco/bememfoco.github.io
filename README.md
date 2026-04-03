# 📰 Bem em Foco — Portal de Conteúdo Otimizado para SEO

🔗 **Acesse:** [https://bememfoco.com.br/](https://bememfoco.com.br/)

---

## 🚀 Visão geral

O **Bem em Foco** é um portal de conteúdo desenvolvido com arquitetura **estática moderna**, focado em performance, SEO e monetização.

Este projeto foi criado não apenas como um site de conteúdo, mas como um **case prático de engenharia frontend e arquitetura web enxuta**, simulando decisões reais de produção.

---

## 🧠 Decisões técnicas (o que diferencia esse projeto)

### ⚡ Arquitetura estática (SSG)

Uso do **Jekyll** para gerar páginas estáticas, eliminando a necessidade de backend tradicional.

**Benefícios:**

* Zero custo de servidor
* Alta performance (TTFB extremamente baixo)
* Super seguro (sem ataques comuns como SQL Injection)

---

### 🔍 SEO como prioridade

O projeto foi estruturado pensando em indexação orgânica:

* URLs amigáveis (`/politica/artigo-exemplo`)
* Uso de **Markdown estruturado**
* Otimização de headings (H1, H2, H3)
* Imagens otimizadas
* Estrutura pronta para **Google AdSense**

---

### 💰 Pronto para monetização

* Layout pensado para anúncios
* Performance otimizada (impacta diretamente no AdSense)
* Conteúdo escalável via `_posts`

---

### 🚀 Deploy simplificado (CI/CD básico)

Deploy automatizado via **GitHub Pages**:

```bash
git push origin main
```

Sem necessidade de:

* VPS
* Docker
* Configuração de servidor

---

## 🛠️ Stack utilizada

* **Jekyll** — Static Site Generator
* **Ruby** — Ambiente do Jekyll
* **HTML5 / CSS3 / JavaScript**
* **Git & GitHub** — versionamento
* **GitHub Pages** — hospedagem

---

## 📂 Estrutura do projeto

```
.
├── _posts        # Conteúdo dinâmico (artigos)
├── _layouts      # Templates base
├── _includes     # Componentes reutilizáveis
├── assets        # CSS, JS e imagens
├── _config.yml   # Configuração do site
└── index.html    # Página inicial
```

---

## ⚙️ Rodando localmente

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
```

Acesse:
[http://localhost:4000](http://localhost:4000)

---

## ✍️ Criação de conteúdo escalável

Novo post:

```
_posts/YYYY-MM-DD-titulo.md
```

Exemplo:

```markdown
---
layout: post
title: "Exemplo de artigo"
date: 2026-04-03
categories: [politica]
image: assets/images/exemplo.jpg
---

Conteúdo aqui...
```

---

## 📈 Escalabilidade do projeto

Mesmo sendo estático, esse projeto foi pensado para evoluir facilmente para:

* Integração com **Headless CMS** (ex: Strapi, Contentful)
* Backend com **Node.js (BFF)** futuramente
* Banco de dados (PostgreSQL)
* APIs para conteúdo dinâmico
* Migração para arquitetura híbrida (SSG + SSR)

---

## 🧪 Possíveis melhorias futuras

* Lazy loading de imagens
* Cache avançado (CDN)
* Dark mode
* Sistema de busca
* Integração com analytics (ex: Firebase / GA4)

---

## 🎯 Objetivo como projeto de portfólio

Este projeto demonstra:

* Capacidade de **tomada de decisão arquitetural**
* Conhecimento em **performance web**
* Entendimento de **SEO técnico**
* Uso de **ferramentas modernas com baixo custo**
* Mentalidade de produto (monetização + crescimento)

---

## 📄 Licença

Baseado no tema **Mundana (MIT License)**
Customizações: © Bem em Foco

---

## 👨‍💻 Autor

**Luis Trindade**
Desenvolvedor Full Stack especializado em aplicações web modernas.

