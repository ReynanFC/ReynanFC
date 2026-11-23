<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:111827,100:1E3A8A&height=200&section=header&text=Reynan%20Ferreira&fontSize=52&fontColor=E2E8F0&fontAlignY=38&desc=Software%20Engineering%20Student%20%7C%20Full%20Stack%20Developer&descSize=16&descAlignY=58&descColor=93C5FD&animation=fadeIn"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=21&pause=1200&color=93C5FD&background=00000000&center=true&vCenter=true&width=650&height=60&lines=%E2%98%95+Java+%7C+Spring+Boot+%7C+Angular;%F0%9F%90%B3+Docker+%7C+PostgreSQL+%7C+Redis;%F0%9F%93%B1+Kotlin+%7C+Jetpack+Compose+%7C+Android;%F0%9F%9A%80+Desenvolvimento+Back-end+%26+Full+Stack;%F0%9F%92%A1+Sempre+aprendendo+algo+novo)](https://git.io/typing-svg)


</div>

---

## 👨‍💻 Sobre mim

Sou estudante de **Engenharia de Software**, com foco em desenvolvimento **Back-end e Full Stack**.

Gosto de ir além de "fazer funcionar": exploro **arquitetura, segurança, persistência, cache, testes automatizados, containerização e CI/CD**. Meu ecossistema principal envolve **Java, Spring Boot, Kotlin e Angular**.

---

## 🛠️ Stack

<div align="center">
  <img src="assets/tech-stack.svg" alt="Tecnologias que utilizo" width="100%"/>
</div>

---

## 🚀 Projetos

<table>
<tr>
<td colspan="2" valign="top">

### 🎟️ [TicketRush](https://github.com/ReynanFC/ticketRush) · 🚧 em desenvolvimento

Plataforma de venda de ingressos em **Kotlin + Spring Boot**, construída em etapas: começa como monólito e evolui para **microsserviços com RabbitMQ**, projetada para aguentar picos de demanda sem vender mais ingressos do que existem.

**Já feito**
- 🏛️ Módulo de catálogo (eventos, setores e lotes) em arquitetura hexagonal
- 🧪 Testes de unidade, de controller e de integração com Testcontainers
- ⚙️ CI no GitHub Actions, Gitflow com PRs e decisões registradas em ADRs
- 🧵 Java 25 com Virtual Threads

**Próximas etapas**
- 🔒 Reserva com controle de concorrência e pedido como máquina de estados
- 📤 Transactional Outbox, consumidores idempotentes, retry com DLQ
- 🔄 Extração para microsserviços com saga orquestrada

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌴 [Caraíva Tours Hub](https://github.com/ReynanFC/caraiva-tours-hub)

Sistema **Full Stack** criado a partir de um problema real de gestão de uma empresa de turismo: reservas, clientes, pagamentos, passeios e indicadores em uma só plataforma.

- 🔐 JWT + RBAC
- ⚡ Dados em tempo real com SSE
- 🧠 Cache e rate limiting com Redis
- 📄 Relatórios em PDF
- 🐳 Docker + NGINX
- 🧪 JUnit + Testcontainers

</td>
<td width="50%" valign="top">

### 🏪 [Inventory & Sales Management](https://github.com/ReynanFC/inventory-sales-management)

API REST para estoque e vendas no varejo, com foco em **regras de negócio, consistência de dados e controle transacional**.

- 📦 Produtos e movimentações de estoque
- 💰 Vendas com controle transacional
- 🗃️ Migrações com Flyway
- 🚦 Fluxo de status da venda com estorno de estoque
- 📚 Documentação com Swagger

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🔎 [Cadê?](https://github.com/p1lloww/cade-backend) · 👥 projeto em equipe · 🎓 POOALAB 2026.2

Achados e perdidos da UCSal: o estudante registra a perda online, a sala cadastra o que chega e o sistema sugere os pares prováveis. **Java 25 + Spring Boot e Angular.**

**Arquitetura e segurança**
- 🧩 Monólito modular com fronteiras validadas por ArchUnit
- 🔐 Login sem senha: código de uso único (hash no PostgreSQL) trocado por JWT, com Spring Security Resource Server
- 🏷️ Autorização por perfil com `@RequiresRole` (anotação própria + reflexão) e teste que barra rota sem perfil

**POOA na prática**
- 🚦 **State** com sealed interface + records nas situações do objeto, da perda e da sugestão
- 🧮 **Strategy + Composite** na nota do cruzamento, explicável critério a critério
- 📣 **Observer** com eventos do Spring após o commit, em **Virtual Threads**
- 🔒 **Lock otimista** (`@Version`) contra convocação dupla e corrida no limite de registros
- 📤 **Transactional Outbox** para os e-mails nunca se perderem nem saírem em dobro

**Qualidade**
- 🧪 Testes com JUnit, MockMvc e Testcontainers
- ⚙️ CI no GitHub Actions com PR revisado por outro integrante

</td>
</tr>
</table>

---

## 📊 Meu GitHub em números

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ReynanFC&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0F172A&title_color=93C5FD&icon_color=60A5FA&text_color=E2E8F0&count_private=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ReynanFC&layout=compact&theme=tokyonight&hide_border=true&bg_color=0F172A&title_color=93C5FD&text_color=E2E8F0&langs_count=8"/>

<br>

<img src="https://streak-stats.demolab.com?user=ReynanFC&theme=tokyonight&hide_border=true&background=0F172A&ring=60A5FA&fire=93C5FD&currStreakLabel=93C5FD"/>

</div>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ReynanFC/ReynanFC/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ReynanFC/ReynanFC/output/github-snake.svg"/>
  <img alt="Cobrinha comendo minhas contribuições" src="https://raw.githubusercontent.com/ReynanFC/ReynanFC/output/github-snake-dark.svg"/>
</picture>
</div>

---

## 🎯 Objetivo

🚀 **Buscando minha primeira oportunidade profissional em desenvolvimento de software**, onde eu possa aplicar meus conhecimentos em arquitetura, construção de APIs robustas e resolução de problemas reais em equipe.

---

<div align="center">

<a href="https://linkedin.com/in/reynan-ferreira-correia-5518a0354">
  <img src="https://img.shields.io/badge/LinkedIn-Reynan%20Ferreira-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/ReynanFC">
  <img src="https://img.shields.io/badge/GitHub-ReynanFC-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

### 💻 Transformando aprendizado em software.

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:111827,100:1E3A8A&height=100&section=footer"/>
