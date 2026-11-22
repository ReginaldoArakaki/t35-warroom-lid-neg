# Simulação War Room Setorial — Liderança, Negociação e Governança (Turma T35)

Suíte completa de materiais instrucionais, interfaces interativas e guias operacionais para a condução da simulação síncrona de 90 minutos de **Liderança, Negociação e Governança em War Room Setorial (Nível 2)** para a Turma T35.

---

## 📌 Visão Geral do Projeto

A experiência pedagógica evolui o aprendizado técnico reativo da crise e-commerce (*Aurora Cyber Monday*) para a gestão sistêmica de **infraestruturas críticas da sociedade**, distribuindo os estudantes em **5 Mesas Multidisciplinares Jigsaw**:

* **MC1 — Banking & Serviços Financeiros:** Foco no autorizador Pix, estornos duplicados e regulamentação BACEN / CVM.
* **MC2 — Hospital & Saúde Integrada:** Foco no Prontuário Eletrônico do Paciente (PEP), risco à vida e regulamentação ANVISA / ANS.
* **MC3 — Logística & Cadeia de Mantimentos:** Foco no SaaS de roteamento, travamento de caminhões e ANTT / Defesa Civil.
* **MC4 — Poder Público (Educação & Serviços):** Foco em exfiltração de PII de 500 mil inscritos, DDoS e regulamentação MEC / CGU / ANPD.
* **MC5 — Poder Público (Distribuição de Energia):** Foco em redes SCADA/OT, apagão em 4 bairros e regulamentação ANEEL / ONS.

---

## 🗂️ Estrutura Recomendada do Repositório

```text
.
├── index.html                 # Landing Page principal (Hub de seleção de perfil)
├── style.css                  # Sistema de design CSS unificado (Dark/Cyber War Room)
├── README.md                  # Documentação principal do repositório
│
├── professor/                 # Portal Exclusivo do Docente
│   └── index.html             # Roteiro síncrono, Fichas de Injeção e Matriz Formativa
│
├── alunos/                    # Hub Interativo das Mesas de Trabalho (MC1 a MC5)
│   └── index.html             # Seletor de setores, papéis Jigsaw e guias A0, W1, W2, W3
│
└── docs/                      # Documentação Pedagógica Consolidada (.md)
    ├── master-roteiro.md      # Roteiro Master de Instrução (Turma T35)
    ├── fluxo-paralelo.md      # Mapeamento minuto a minuto (Facilitador vs. Alunos)
    └── deploy-github.md       # Guia passo a passo de implantação no GitHub Pages
```

---

## 🚀 Publicação no GitHub Pages

1. **Subir os arquivos para o repositório Git:**
   - Execute `git init`, `git add .`, `git commit -m "feat: Adiciona suite interativa da War Room T35"`.
   - Conecte ao seu repositório remoto: `git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git`.
   - Envie as alterações: `git push -u origin main`.

2. **Ativar o GitHub Pages:**
   - Acesse no GitHub: **Settings** -> **Pages**.
   - Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
   - Clique em **Save**. O site estará disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

---

## 🎨 Legenda de Cores dos Post-its no Miro

- 🟢 **Verde (Fato / Evidência):** Logs auditados, hashes e confirmações forenses.
- 🔵 **Azul (Hipótese / Suposição):** Diagnósticos em investigação e vetores prováveis.
- 🌸 **Rosa (Ponto Cego / Lacuna):** Falhas históricas (A0) ou dados não confirmados.
- 🟡 **Amarelo (Decisão / SLA):** Ações de contenção com responsável RACI e prazos fatais.
- 🟧 **Laranja (Concessão / Trade-off):** Acordos e riscos aceitos na negociação regulatória.

---

## ⚖️ Dilemas Éticos Executivos

- 🔴 **Postura Ocultação (Modelo Uber 2016):** Abafar o incidente e ocultar dados de reguladores.
- 🟢 **Postura Transparência Radical (Modelo NHS 2017):** Notificação tempestiva e comunicação aberta.
