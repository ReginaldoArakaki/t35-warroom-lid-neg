# T35 · Liderança e Negociação em War Room

Material da aula de 24/11/2026 (Inteli · Engenharia de Software, módulo 12). São 90 min em 3 partes (Conceito, Dinâmica 1, Dinâmica 2), com 5 mesas Jigsaw (MC1–MC5) e uma crise diferente por setor. Todos os cenários são fictícios.

## Estrutura

```
.
├── README.md
├── docs/                      ← site dos alunos (GitHub Pages)
│   ├── index.html             página de entrada
│   ├── alunos.html            página da mesa: papéis, A0, W1, ficha, triagem, W2, W3, exportação
│   └── style.css
├── professor/                 ← NÃO publicar
│   ├── painel-professor.html  roteiro, fichas, códigos, sorteio de posturas, checklist, rubrica, cronômetro
│   └── cartoes-ceo.md         envelopes para imprimir + códigos + rotação dos fiscais
└── material/
    ├── master-roteiro.md      roteiro consolidado
    └── fluxo-paralelo.md      professor × estudantes, minuto a minuto
```

## Linha do tempo

| Min | Parte | Atividade |
| :--- | :--- | :--- |
| 00–20 | Conceito | Abertura, A0 da Aurora, Uber 2016 × NHS 2017 |
| 20–50 | Dinâmica 1 | Mesas, envelopes, W1, pitch de 1,5 min |
| 50–82 | Dinâmica 2 | Códigos (50), W2 e boatos (58 e 66), fiscalização cruzada (70–76), W3 (76–82) |
| 82–90 | Fechamento | Revelação, síntese, exit ticket e exportação |

## Uso em sala

1. Antes da aula, abra `professor/painel-professor.html` no seu computador. O painel sorteia as posturas (3 Ocultação, 2 Transparência) e guarda tudo neste navegador.
2. Imprima os envelopes de `professor/cartoes-ceo.md`.
3. Os alunos abrem `docs/alunos.html` (pelo link do GitHub Pages ou o arquivo). Aos 50 min, anuncie o código de cada mesa.
4. Ao final, cada mesa exporta o dossiê `.txt` e o W2 `.csv` e envia ao professor.

As páginas funcionam offline. Os ícones vêm de uma CDN; sem internet, aparecem só os textos.

## Publicação no GitHub Pages

Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/docs`.

**Privacidade.** Em repositório privado, o Pages exige plano pago ou GitHub Education, e o site publicado continua **público**. Por isso o material do professor fica fora de `docs/`. Se o repositório for público, a pasta `professor/` também fica visível no GitHub: nesse caso, mantenha `professor/` fora do repositório (ou num repositório privado separado). Os códigos de liberação estão em `alunos.html` só como hash, o que basta para evitar espiada casual, não para proteger de quem lê o código.

## Comandos git

```bash
git init -b main
git add .
git commit -m "Material T35 War Room: 5 mesas, painel do professor e roteiro"
git remote add origin https://github.com/<usuario>/t35-war-room.git
git push -u origin main
```

> Pasta dentro do OneDrive: o OneDrive pode sincronizar a pasta `.git` no meio de uma operação e corromper o repositório. Se possível, mantenha o clone fora do OneDrive, ou pause a sincronização durante `commit` e `push`.

## Referências normativas usadas

- LGPD, art. 48; Resolução CD/ANPD nº 15/2024 (comunicação de incidente em até 3 dias úteis).
- Resolução CMN nº 4.893/2021 (bancos) e Resolução BCB nº 85/2021 (instituições de pagamento).
- Os demais prazos das fichas são metas fictícias do playbook.
