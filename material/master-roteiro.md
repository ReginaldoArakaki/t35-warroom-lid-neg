# Master Roteiro: Liderança, Negociação e Governança em War Room (Turma T35)

Inteli · Engenharia de Software, módulo 12 · 24/11/2026, 10h · 90 min · atividade obrigatória, formativa e não ponderada.

Este roteiro serve à aula de **Liderança e Negociação em War Room**. Ela continua a aula da Aurora Varejo (Cyber Monday, Secure Code Game Level 1). Os alunos são estagiários que já veem salas de crise no trabalho, mas pouco participam delas. A aula põe cada um num papel com voz e responsabilidade, em cinco mesas com crises diferentes.

> Todos os cenários, organizações e números são fictícios. O único prazo legal usado como referência é o da ANPD. Os demais prazos das fichas são **metas do playbook**, criadas para a simulação (ver seção 6).

---

## 1. Do Nível 1 ao Nível 2

| Dimensão | Nível 1 (Aurora Cyber Monday) | Nível 2 (War Room Setorial T35) |
| :--- | :--- | :--- |
| Foco | Diagnóstico técnico de código e infraestrutura | Governança, alçadas, negociação e comunicação |
| Organização | Grupos PBL G1–G5 em silos | Mesas Jigsaw MC1–MC5, um integrante de cada grupo |
| Ambiente | E-commerce privado | Cinco setores críticos, um por mesa |
| Prazos | Notificação tratada como detalhe | Prazos de norma (ANPD) e metas do playbook definidas pela mesa |
| Evidência | Discussão informal | Registro W2 com fato, hipótese e lacuna separados |

## 2. Linha do tempo única (3 partes)

| Minuto | Parte | O que acontece | Artefato |
| :--- | :--- | :--- | :--- |
| 00–05 | 1 · Conceito | Abertura e objetivo da aula | — |
| 05–12 | 1 · Conceito | Debrief da Aurora: o que fizemos bem, nosso ponto cego | A0 |
| 12–20 | 1 · Conceito | Uber 2016 × NHS 2017, armadilha do resgate, legenda de cores | — |
| 20–25 | 2 · Dinâmica 1 | Formação das mesas Jigsaw, papéis, envelopes ao CEO | — |
| 25–40 | 2 · Dinâmica 1 | Carta de arquitetura da War Room | W1 |
| 40–50 | 2 · Dinâmica 1 | Pitch de 1,5 min por mesa | W1 |
| 50–52 | 3 · Dinâmica 2 | Professor anuncia o código de liberação de cada mesa | Ficha |
| 52–70 | 3 · Dinâmica 2 | Triagem, contenção, negociação; boatos aos 58 e 66 min | W2 |
| 70–76 | 3 · Dinâmica 2 | Fiscalização cruzada | W2 |
| 76–82 | 3 · Dinâmica 2 | Plano integrado e aceite do risco residual | W3 |
| 82–85 | Fechamento | Revelação dos envelopes | — |
| 85–88 | Fechamento | Síntese do professor (3 lições) | — |
| 88–90 | Fechamento | Exit ticket e exportação dos dossiês | — |

## 3. Mesas Jigsaw e papéis

Com ~30 alunos, cada mesa tem 6 integrantes: um de cada grupo PBL e um sexto que atua como **fiscal cruzado**.

| Papel | Origem | Responsabilidade |
| :--- | :--- | :--- |
| Executivo de Negócio (CEO/COO) | G1 | Decisão final; recebe o envelope de postura |
| Cloud & Infra | G2 | Isolamento, contingência, restauração |
| Poder Público & Compliance | G3 | Reguladores, prazos, LGPD |
| Auditor Independente | G4 | Preservação de evidência; barra hipótese tratada como fato |
| Consultor Cyber | G5 | Causa raiz, contenção sem destruir evidências |
| Fiscal cruzado (6º) | qualquer | Entre 70 e 76 min, fiscaliza a mesa seguinte |

Rotação dos fiscais: MC1→MC2, MC2→MC3, MC3→MC4, MC4→MC5, MC5→MC1.

## 4. Dilema ético: envelopes sorteados

Os casos de referência são **Uber 2016** (ocultação do vazamento, pagamento ao atacante apresentado como recompensa por bug, condenação do CSO) e **NHS / WannaCry 2017** (comunicação aberta, recusa de resgate, contingência manual).

Cada CEO recebe um envelope lacrado, em papel, com uma das posturas: **3 de Ocultação e 2 de Transparência**. A distribuição é **sorteada entre as mesas**, para que a comparação no fechamento não seja confundida com o setor. O painel do professor faz o sorteio e guarda o resultado. Os textos para impressão estão em `professor/cartoes-ceo.md`.

Se uma mesa ceder à ocultação, o professor registra o momento para o debrief. Não há perda de pontos.

## 5. Artefatos

- **A0 (05–12):** pontos cegos e acertos da Aurora.
- **W1 (25–50):** reguladores, autoridade única de parada, metas de detecção, contenção e notificação, canal out-of-band, RACI. A mesa preenche sem modelo pronto.
- **W2 (52–76):** hora, categoria (cor), evento ou decisão, responsável RACI, status frente à meta do W1, evidência.
- **W3 (76–82):** 2 ações imediatas e 1 controle preventivo, cada um com responsável, prazo, critério de aceite e evidência; aceite do risco residual pelos 5 papéis (papel + iniciais, simulação sem valor jurídico).

## 6. As cinco fichas de crise

A ficha de cada mesa fica lacrada na página `alunos.html` até o professor anunciar o código, aos 50 min (horário simulado 10h15).

| Mesa | Código | Cenário | Reguladores |
| :--- | :--- | :--- | :--- |
| MC1 · Banking | LIQUIDEZ | Credencial de API de um parceiro de integração dispara estornos Pix em massa; boato de falência | BACEN (Res. CMN 4.893/2021 para bancos; Res. BCB 85/2021 para instituições de pagamento), CVM, ANPD |
| MC2 · Saúde | PLANTAO | Ransomware no prontuário eletrônico de 3 hospitais | ANVISA, ANS, CFM, ANPD |
| MC3 · Logística | COMBOIO | Credenciais do SaaS de telemetria sequestradas; travas de 1.200 caminhões bloqueadas | ANTT, ANTAQ, Defesa Civil, ANPD |
| MC4 · Educação | INSCRICAO | Vazamento de 500 mil inscritos e DDoS no último dia de inscrição | MEC, CGU, ANPD, LAI |
| MC5 · Energia | SUBESTACAO | Comandos anômalos no SCADA abrem disjuntores; apagão em 4 bairros | ANEEL, ONS, Defesa Civil, ANPD |

**Prazos.** A Resolução CD/ANPD nº 15/2024 fixa a comunicação à ANPD e aos titulares em até **3 dias úteis** a partir do conhecimento de que o incidente afetou dados pessoais, com possibilidade de complementação em 20 dias úteis; o registro do incidente é mantido por pelo menos 5 anos. Os demais prazos das fichas (15 min, 1 h, 4 h, 24 h etc.) são metas fictícias do playbook. No W1, a mesa decide quais metas adota e de onde elas vêm.

## 7. Legenda de cores

- 🟢 **Verde · Fato:** confirmado por log, teste ou telemetria.
- 🔵 **Azul · Hipótese:** diagnóstico pendente. Boato entra aqui, com a fonte anotada.
- 🌸 **Rosa · Lacuna:** o que a mesa ainda não sabe.
- 🟡 **Amarelo · Decisão:** medida aprovada com responsável, prazo e evidência.
- 🟧 **Laranja · Concessão:** trade-off aceito na negociação.

A página das mesas registra a classificação escolhida, sem indicar resposta certa. A discussão acontece na mesa e no debrief.

## 8. Rubrica formativa (0–2 por critério, total 10)

| Critério | 0 | 1 | 2 |
| :--- | :--- | :--- | :--- |
| A0 · Pontos cegos | Não identifica falhas | Falhas genéricas | Lacunas precisas de alçada, prazo e evidência |
| W1 · Arquitetura | Sem papéis ou prazos | Papéis sem autoridade única ou metas | RACI, autoridade única, reguladores e metas do setor |
| W2 · Resposta e evidência | Trata boato como fato | Mistura fato, hipótese e lacuna | Decisões com responsável e evidência; boato como hipótese |
| Dilema ético e fiscalização | Cede à ocultação ou não se sustenta | Resiste, mas sem evidência | Sustenta a transparência com evidências do W2 e alçadas do W1 |
| W3 · Governança preventiva | Sem plano | Ações vagas ou sem dono | 2 ações + 1 controle completos e aceite registrado |
