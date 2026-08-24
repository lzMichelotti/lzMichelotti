<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTJjMzQ1NmY4OTAxMjM0NTY3ODkwMTIzNDU2Nzg5MDEyMzQ1Njc4OSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/L8K62iTDkzGX6/giphy.gif" width="600" />
</div>
<div align="center">
  <h1>Lorenzo Michelotti Palma</h1>
  <h3>🐍 Desenvolvedor Backend (Python) | ⚡ APIs & Integrações | 🐘 PostgreSQL | 🤖 Automação</h3>

  <p>
    Formando em <b>Redes de Computadores (UFSM)</b> · conclusão em dez/2026<br>
    <b>Estagiário de Desenvolvimento na MagniCred</b> e <b>Bolsista de Iniciação Científica (UFSM)</b>
  </p>

  <p>
    Backend com Python: APIs, modelagem de banco e automação de processos reais.<br>
    Gosto de decisão técnica justificada — e de deixar o porquê escrito no README.
  </p>

  <a href="https://www.linkedin.com/in/lorenzo-michelotti-palma/">
    <img src="https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:lzmichelotti@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</div>

<br>
<hr>
<br>

## 🛠️ Tecnologias

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br><br>
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</div>

<br>
<hr>
<br>

## 🚀 Principais Projetos

### 🌱 [Hortas Urbanas](https://github.com/lzMichelotti/Hortas_Urbanas)

Plataforma de gestão de hortas comunitárias, desenvolvida como produto tecnológico de uma pesquisa sobre agricultura urbana e resiliência climática (Edital FAPERGS). O público-alvo — em boa parte idoso, com internet instável e Android antigo — virou restrição de engenharia: idempotência para sobreviver a reenvios, ETag + 304 para economizar banda, geometria simplificada no banco e upload de foto direto ao storage sem passar pela API.

`73 endpoints` · `30 migrations` · `243 testes` · deploy em VPS com Docker Compose e TLS automático

- **Stack:** Python (FastAPI), PostgreSQL + PostGIS, SQLAlchemy/Alembic, Docker, Caddy, React + TypeScript, Capacitor (Android/PWA)

---

### 🏢 [meucondominIA](https://github.com/meucondominIA/meucondominIA)

Assistente de WhatsApp com IA para condomínios: o morador tira dúvida do regimento, reserva área comum e abre ocorrência sozinho; o síndico só é acionado quando alguém precisa decidir de fato. O RAG cita sempre o artigo de origem e admite quando não sabe — inventar regra é o único erro inaceitável aqui.

`922 testes` · roteador como máquina de estados pura · regras críticas em constraint no Postgres, não em `if` no Python · RAG com avaliação medida contra gabarito

- **Stack:** Python assíncrono (FastAPI), PostgreSQL + pgvector, OpenAI, RLS multi-tenant, testcontainers

<br>
<div align="center">
  <sub><i>"O código é apenas a ferramenta; o verdadeiro desenvolvimento está em resolver problemas complexos com arquiteturas simples e eficientes."</i></sub>
</div>
