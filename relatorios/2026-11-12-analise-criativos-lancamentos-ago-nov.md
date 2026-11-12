# Análise de criativos — lançamentos pagos IER26AGO, IER26SET e IER26NOV

Data da análise: 12/11/2026
Conta: CONTA ANUNCIOS BRUNA LACERDA (act_367662610821507)
Produto da frente: Ingresso VIP — Imersão Especialista em Regularização (R$47)
Produto final (DDA): R$1.797

## Fontes

| Planilha | Período coberto (MetaAds) |
|---|---|
| IER26AGO - 15/08 - Lançamento PAGO - Trackeamento | 24/07 → 14/08 |
| IER26SET - 12/09 - Lançamento PAGO - Trackeamento | 15/08 → 11/09 |
| IER26NOV - 07/11 - Lançamento PAGO - Trackeamento | 11/09 → 07/11 (já inclui o ciclo de outubro) |

Os links 1 e 2 enviados eram a mesma planilha (NOV). Não há planilha separada de outubro: o período
de outubro está dentro da planilha de novembro.

Métricas por criativo: aba **Planilha Kevin** de cada planilha (só campanhas de venda de ingresso, LP),
sem as linhas "Total geral" e sem o bloco de linhas duplicadas da planilha NOV.
"Ingressos" = compras do Gerenciador. "Vendas DDA" = vendas do produto final atribuídas ao criativo.
Variações do mesmo vídeo foram agrupadas pelo número base (ex.: `VID_79`, `VID_79_E` e `VID_79_F` → `VID_79`).
Ranking completo: `relatorios/2026-11-12-ranking-criativos-ago-set-nov.csv`.

## Visão geral

| Lançamento | Investimento (LP) | Ingressos | CPA | Vendas DDA |
|---|---:|---:|---:|---:|
| AGO | R$47.495 | 267 | R$178 | 31 |
| SET | R$71.631 | 361 | R$198 | 47 |
| NOV | R$69.259 | 413 | R$168 | 9 (atribuição ainda incompleta) |
| **Total** | **R$188.385** | **1.041** | **R$181** | **87** |

## Criativos que mais escalaram em vendas

Ordenados por ingressos vendidos, somando os 3 lançamentos.

| # | Criativo | Lançamentos | Gasto | Ingressos | CPA | Vendas DDA | Leitura |
|---|---|---|---:|---:|---:|---:|---|
| 1 | **VID_161** | AGO/SET/NOV | R$15.590 | 95 | R$164 | 9 | Campeão de agosto (84 vendas, CPA R$157). Saturou: SET CPA R$202, NOV R$405 |
| 2 | **VID_210_SS** | SET/NOV | R$10.564 | 92 | R$115 | 0 | Campeão de novembro em volume (71 vendas). Vai direto pro checkout |
| 3 | **VID_181** | SET/NOV | R$20.987 | 91 | R$231 | 9 | Maior gasto. Campeão de setembro (63 vendas). Copy "faturar 10 mil/mês" |
| 4 | **VID_211_SS** | SET/NOV | R$4.988 | 57 | R$88 | 0 | Menor CPA entre os que escalaram. Direto pro checkout |
| 5 | **VID_133** | AGO/SET/NOV | R$11.175 | 54 | R$207 | 7 | Constante nos 3 lançamentos, CPA alto |
| 6 | **VID_27** | AGO/SET/NOV | R$8.182 | 51 | R$160 | 6 | Constante. Voltou a escalar em NOV (28 vendas, CPA R$150) |
| 7 | **VID_RMKT_03** | AGO/SET/NOV | R$6.585 | 45 | R$146 | 7 | Remarketing. Melhor ROAS de DDA entre os de volume (1,9) |
| 8 | VID_60 | AGO/SET/NOV | R$7.546 | 42 | R$180 | 5 | Caiu em NOV (CPA R$350) |
| 9 | VID_212_SS | SET/NOV | R$4.909 | 40 | R$123 | 0 | Direto pro checkout |
| 10 | VID_160 | AGO/SET/NOV | R$7.971 | 40 | R$199 | 6 | 14 variações; nenhuma decolou |
| 11 | IMG_75 | SET/NOV | R$6.808 | 39 | R$175 | 4 | Melhor imagem estática |
| 12 | VID_79 | SET/NOV | R$7.044 | 37 | R$190 | 2 | Bom em SET (30 vendas), sumiu em NOV |
| 13 | IMG_ROLETA_03 | AGO/SET/NOV | R$5.790 | 36 | R$161 | 5 | Gamificação (roleta). Único dos testes "jogo" que escalou |
| 14 | IMG_74 | SET/NOV | R$4.214 | 33 | R$128 | 1 | Subindo em NOV (25 vendas, CPA R$124) |

### Pontos de atenção

1. **Os criativos `_SS` vendem ingresso barato, mas não vendem o produto final.** Somados, VID_210, 211,
   212 e 169 trouxeram 216 ingressos (≈21% de todos) com CPA ≈ R$110, e **zero vendas DDA**. O link deles
   vai direto ao checkout (pay.hub.la), sem LP, com a copy "Últimas vagas… ou você entra agora, ou
   assiste de fora". Eles trazem volume de ingresso, mas um comprador menos qualificado. Ressalva: a
   atribuição DDA de NOV ainda está incompleta (9 atribuídas contra 60 compradores no Relatório).
2. **Os vídeos que mais trouxeram compradores DDA passam pela LP:** VID_161 (9), VID_181 (9), VID_133 (7),
   VID_RMKT_03 (7), VID_27 (6), VID_160 (6). Esse é o grupo de referência para as VSLs.
3. **Fadiga:** VID_161 e VID_60 perderam força a cada lançamento. VID_27, RMKT_03 e IMG_74 se mantiveram
   ou melhoraram.
4. **Testes de tema explícito tiveram pouca verba e nenhum escalou:** 170 DESEJO_TEMPO E FAMÍLIA
   (R$1.302, 6 vendas, CPA R$217, um pouco acima da média), 173 OBJEÇÃO_NÃO SABER RESPONDER (R$612, 2 vendas),
   171 ERRO COMUM (R$399, 1 venda), 172 QUEBRA DE CRENÇA (R$152, 0 vendas). Gamificação (caça-níquel,
   raspadinha, quiz) não escalou, exceto ROLETA_03.

## O que o público diz (pesquisa de captação, 648 respostas nos 3 lançamentos)

- **Perfil:** 41% engenheiros civis, 32% arquitetos. 55% ainda não atuam com regularização ("quero
  começar"). A faixa de faturamento mais comum é R$2.500–5.000.
- **Quem mais compra o DDA:** engenheiro civil (22,6% compram, contra 14,9% dos arquitetos), quem já
  presta serviço (21,7%) e quem fatura R$5–10 mil (20,8%). Quem fatura abaixo de R$1 mil compra menos
  (10,9%).
- **Maior sonho** (respostas abertas, por palavra-chave). Os percentuais "Compradores DDA" vêm só de
  quem a planilha marca como "COMPROU".

| Tema | Todos | Compradores DDA |
|---|---:|---:|
| Liberdade / independência / estabilidade financeira | 22% | **29%** |
| Faturar mais / renda extra | 16% | 17% |
| Ter o próprio escritório / negócio | 7% | **13%** |
| Família / tempo / qualidade de vida | 8% | **13%** |
| Sair do CLT / viver da profissão | 8% | 6% |

- **O que esperam aprender:** passo a passo / processo completo (42%), documentação, cartório, órgãos e
  CND (16%), começar uma nova área (14%), **captar clientes** (10% no geral, **16% entre compradores DDA**).

## Tema recomendado e as 3 VSLs curtas

Limitação: o texto do anúncio é praticamente o mesmo em todos os criativos. O tema de cada vídeo está
no próprio vídeo, e não consegui abrir os arquivos. No Drive estão sem transcrição e acima do limite de
download; o servidor de imagens do Meta está bloqueado neste ambiente. A única copy diferente entre os
campeões é a do VID_181 ("aprender em 1 dia… abrir caminho para faturar 10 MIL por mês"). As VSLs
abaixo partem dela, da pesquisa e dos números acima. **Antes de produzir, confirmar o assunto de
VID_161, VID_181, VID_133, VID_27 e VID_RMKT_03.**

### Tema principal (VSL 1) — "Uma nova fonte de renda de R$10 mil/mês com regularização"
- **Por quê:** é a promessa do criativo de maior gasto (VID_181, 9 DDA) e casa com o sonho nº 1 dos
  compradores DDA: liberdade financeira mais renda extra, 46% somados.
- **Público:** engenheiros civis e arquitetos que faturam R$2,5–10 mil.
- **Estrutura (60–90 s):** gancho com o número (R$10 mil/mês) → por que existe tanto imóvel irregular
  (oportunidade de mercado) → prova (Bruna e alunos) → o que a Imersão entrega em 1 dia → oferta R$47 → CTA para a LP.

### VSL 2 — "O passo a passo que a faculdade não te ensinou"
- **Por quê:** "passo a passo / processo completo" é a expectativa nº 1 (42%). Documentação, cartório e
  órgãos vêm em seguida. Isso também ataca a insegurança técnica testada no 173 ("não saber responder ao cliente").
- **Estrutura:** gancho "você se formou e ninguém te ensinou a regularizar um imóvel" → as 3–4 etapas
  (visita → levantamento e documentação → prefeitura e cartório → entrega) → o erro comum que trava quem
  começa → "na Imersão eu mostro cada etapa, ao vivo" → CTA.

### VSL 3 — "Seu escritório, seus horários: liberdade e tempo com a família"
- **Por quê:** "próprio negócio" e "família/tempo" quase dobram entre os compradores DDA (13% cada,
  contra 7–8% no geral). O 170 DESEJO_TEMPO E FAMÍLIA vendeu com pouca verba (CPA R$217) e merece um
  teste com roteiro mais forte.
- **Estrutura:** cena do dia a dia (trânsito, CLT, obra sem fim) → virada: serviço de regularização com
  ticket alto, feito do próprio escritório → como captar os primeiros clientes (16% dos compradores DDA
  querem isso) → convite para a Imersão → CTA.

### Como rodar o teste
- Enviar as 3 VSLs **para a LP**, e não direto ao checkout. Os criativos `_SS` mostram que a ida direta
  vende ingresso barato, mas não vende o DDA.
- Usar os 4 posicionamentos do Instagram (Feed, Perfil, Reels, Stories), conforme as regras do repositório.
- Julgar os criativos por vendas DDA e CPA de ingresso, não só por CPA.
