# Master Roteiro Integrado de Instrução: Liderança, Negociação e Governança em War Room (Turma T35)

Este documento consolida a totalidade das análises pedagógicas, diretrizes metodológicas, estruturas operacionais e simulações de crise desenvolvidas para a condução da aula de 90 minutos de **Liderança, Negociação e Governança em War Room (Turma T35)**. O roteiro orienta a transição pedagógica dos estudantes do diagnóstico técnico reativo para a operação sistêmica de salas de comando multidisciplinares em infraestruturas críticas da sociedade.

---

## 1. Visão Geral e Fundamentação Pedagógica

### 1.1 A Virada de Chave: Do Nível 1 ao Nível 2
Na simulação anterior (*Aurora Varejo — Cyber Monday*), os estudantes vivenciaram o diagnóstico reativo de falhas de código sob a perspectiva de silos operacionais isolados. A nova aula eleva a complexidade pedagógica para o **Nível 2**, onde o foco migra da resolução puramente técnica para a **operação sistêmica de salas de comando multidisciplinares**.

| Dimensão Pedagógica | Nível 1 (Aurora Cyber Monday) | Nível 2 (War Room Setorial - T35) |
| :--- | :--- | :--- |
| **Foco Operacional** | Diagnóstico técnico de código e infraestrutura. | Governança sistêmica, alçadas e gestão de crise. |
| **Estrutura Organizacional** | Silos funcionais (Dev vs. Ops vs. Negócio). | Mesas Multidisciplinares Jigsaw (5 Papéis). |
| **Ambiente de Impacto** | E-commerce privado (prejuízo financeiro/imagem). | Infraestruturas críticas da sociedade (risco de vida, apagão). |
| **Marcos Regulatórios** | Notificação pontual ou omissão de compliance. | SLAs coercitivos (BACEN, ANVISA, ONS, ANPD, CGU). |
| **Gestão de Evidências** | Discussões informais e pontuais. | Rastreabilidade forense rigorosa no Miro (Fatos vs. Fakes). |

---

## 2. Metodologia Jigsaw e Matriz de Papéis nas Mesas

Para simular a complexidade de uma War Room executiva, a turma é organizada em **5 Mesas Multidisciplinares (MC1 a MC5)**. Cada estudante assume um papel especializado indispensável para a governança do setor:

1. 👔 **Executivo de Negócio (CEO / Board):** Tomador de decisão de alto nível, porta-voz institucional e guardião da orientação ética (detém o cartão secreto de Transparência Radical vs. Ocultação).
2. ☁️ **Especialista em Cloud/Infra (CTO / DevOps):** Responsável pela contenção técnica, isolamento de rede, ativação de rotas *out-of-band* e preservação de logs.
3. ⚖️ **Poder Público & Compliance (CLO / DPO):** Guardião do cumprimento dos SLAs coercitivos de notificação regulatória e cálculo de sanções administrativas e legais.
4. 🔍 **Auditor Independente & Forense:** Fiscal da legenda estrita de post-its no Miro e da validação de evidências técnicas que sustentam as decisões.
5. 🛡️ **Consultor Técnico & Gestão de Riscos:** Projetista do plano de continuidade operacional e mapeador dos riscos residuais pós-incidente.

---

## 3. O Dilema Ético de Liderança: Estudos de Caso Comparados

A facilitação docente deve tensionar a tomada de decisão das mesas contrapondo dois modelos reais de governança em momentos de crise:

* **🔴 O Anti-Padrão: Caso Uber (2016):** Ocultação ativa do vazamento de 57 milhões de registros, pagamento secreto de resgate mascarado como *bug bounty* e imposição de NDAs sem valor jurídico. *Resultado:* Processo criminal e condenação do CISO por obstrução de justiça.
* **🟢 O Padrão Ouro: Caso NHS / WannaCry (2017):** Transparência radical imediata, comunicação aberta com o público, recusa absoluta a financiar criminosos e ativação do *fallback* analógico (papel/rádio) para manter UTIs operacionais. *Resultado:* Preservação da confiança pública e apoio institucional acelerado.

---

## 4. Arquitetura de Artefatos Incrementais (A0 -> W1 -> W2 -> W3)

O trabalho prático dos estudantes no Miro é estruturado pela entrega progressiva de 4 artefatos principais:

* **Artefato A0 — Mapeamento de Pontos Cegos (00-20 min):** Resgate das falhas e impasses vividos na crise anterior da Aurora Varejo (ex.: atraso na notificação, falta de autoridade única de parada).
* **Artefato W1 — Carta de Arquitetura da War Room Setorial (20-50 min):** Definição pré-crise da topologia do setor, órgãos reguladores diretos, SLAs de notificação preliminar, Matriz RACI de Autoridade de Parada e canal emergencial *out-of-band*.
* **Artefato W2 — Registro Único de Resposta à Crise Setorial (50-78 min):** Tabela de controle em tempo real contendo: Hora da Decisão, Evento/Ação, Decisor RACI (*Accountable*), Status do SLA Regulatório e Evidência Forense Anexada.
* **Artefato W3 — Plano Integrado de Governança e Continuidade (78-82 min):** Formalização de 4 ações imediatas de recuperação, 2 controles de governança preventiva para evitar reincidência e o aceite digital dos riscos residuais por todos os membros da mesa.

---

## 5. Detalhamento Técnico das 5 Fichas de Injeção de Crise Setorial

Às 10h15 simuladas (minuto 50 da aula), o professor libera a injeção surpresa de emergência adaptada para o setor de cada mesa:

### 5.1 MC1 — Banking & Serviços Financeiros
* **Cenário:** Injeção de transações atípicas no autorizador do Pix, gerando estornos duplicados e inconsistência contábil em contas corporativas, com boatos de falência viralizando.
* **Marcos Regulatórios:** BACEN (Res. BCB 85/2021), CVM e ANPD (Art. 48 LGPD).
* **SLAs Coercitivos:** Isolamento de módulos em **15 min**; Nota pública em **1h**; Notificação preliminar ao BACEN em **2h**.

### 5.2 MC2 — Hospital & Saúde Integrada
* **Cenário:** Ransomware criptografa o Prontuário Eletrônico do Paciente (PEP) em 3 hospitais de grande porte, paralisando dados cirúrgicos e históricos de medicação em UTIs.
* **Marcos Regulatórios:** ANVISA, ANS, CFM e ANPD (Dados Sensíveis).
* **SLAs Coercitivos:** Contingência analógica em papel em **5 min**; Isolamento de rede em **10 min**; Notificação formal em **4h**.

### 5.3 MC3 — Logística & Cadeia de Mantimentos
* **Cenário:** Sequestro de credenciais no SaaS de telemetria paralisa travas eletrônicas de 1.200 caminhões de alimentos e combustível em região metropolitana.
* **Marcos Regulatórios:** ANTT, ANTAQ, Defesa Civil e ANPD.
* **SLAs Coercitivos:** Desbloqueio emergencial de travas em **20 min**; Roteamento alternativo em **30 min**; Notificação à Defesa Civil em **1h**.

### 5.4 MC4 — Poder Público (Educação & Gov)
* **Cenário:** Exfiltração massiva de PII de 500 mil inscritos em exame nacional combinada com ataque DDoS no portal de inscrições a 8 horas do encerramento do prazo.
* **Marcos Regulatórios:** MEC, CGU, ANPD e Lei de Acesso à Informação (LAI).
* **SLAs Coercitivos:** Ativação de Scrubbing Center DDoS em **30 min**; Edital de prorrogação em **1h**; Notificação ANPD/CGU em **24h**.

### 5.5 MC5 — Energia Elétrica & Smart Grid
* **Cenário:** Comando anômalo no sistema SCADA abre disjuntores de alta tensão, causando blackout em 4 bairros centrais e afetando semáforos, metrô e hospitais.
* **Marcos Regulatórios:** ANEEL, ONS, Defesa Civil e ANPD.
* **SLAs Coercitivos:** Alerta crítico ao ONS em **15 min**; Geradores emergenciais em hospitais em **20 min**; Recomposição manual em **45 min**.

---

## 6. Dinâmica de Fatos vs. Fakes no Miro (Cultura da Evidência)

Para simular a pressão e o ruído da crise, o Miro impõe o uso estrito de um código de cores para post-its:

* 🟢 **Verde (Fato / Evidência):** Informação confirmada por logs ou testes forenses.
* 🔵 **Azul (Hipótese):** Diagnóstico preliminar pendente de validação.
* 🌸 **Rosa (Ponto Cego):** Lacuna crítica de conhecimento a ser investigada.
* 🟡 **Amarelo (Decisão / SLA):** Contenção aprovada com responsável RACI.
* 🟧 **Laranja (Concessão / Trade-off):** Compromisso assumido com o regulador/diretoria.

---

## 7. Matriz de Avaliação Formativa e Rubrica Docente

| Critério Avaliado | Pontuação 0 | Pontuação 1 | Pontuação 2 |
| :--- | :--- | :--- | :--- |
| **Análise de Pontos Cegos (A0)** | Omissões completas. | Pontos cegos genéricos. | Diagnóstico preciso com falhas de alçada e SLAs. |
| **Arquitetura War Room (W1)** | Estrutura sem papéis. | Papéis definidos sem RACI. | RACI completo, reguladores e canal out-of-band. |
| **Resposta à Crise (W2)** | Ações desconectadas. | Contenção sem SLA legal. | Ações auditáveis, evidências anexadas e SLAs mantidos. |
| **Governança Preventiva (W3)** | Sem plano futuro. | Ações genéricas sem dono. | Controles auditáveis, dono RACI e riscos aceitos. |
| **Arguição e Auditoria** | Sem justificativas. | Resposta parcial ao fiscal. | Defesa técnica firme fundamentada nos registros W2. |
