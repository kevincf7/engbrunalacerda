# [REGRA] [LP] ABO 1-5-1 — reagrupamento dos criativos que não rodaram

Criado em: 14/11/2026

## Contexto

Das 31 campanhas `[REGRA] [LP] [CBO] … [1-1-1]` (ver `2026-11-12-regra-lp-1-1-1-criativos-desde-08-11.md`),
só 4 gastaram em 13–14/11: VID_252 (R$53,23), VID_254 (R$42,20), VID_264 (R$51,51, 1 compra) e IMG_08 (R$62,24).
As outras 27 tiveram zero impressões, mesmo com campanha, conjunto e anúncio ATIVOS, anúncios aprovados e conta ativa.

Diagnóstico provável (inferido; a ferramenta não lê o diagnóstico de entrega): **sobreposição de leilão**.
As 31 campanhas eram cópias idênticas (mesmo público, pixel, evento de compra e posicionamentos), e a Meta só coloca
um conjunto do mesmo anunciante em cada leilão. Por isso concentrou a entrega em poucas campanhas.

## O que foi feito

- As 27 campanhas 1-1-1 zeradas foram **pausadas**. As 4 que gastaram continuam ativas.
- Os 27 criativos foram reagrupados em **5 campanhas ABO, separadas por formato**, com um conjunto por criativo e R$50/dia
  em cada conjunto. Total: 27 conjuntos × R$50 = **R$1.350/dia**.
- Início: **15/11/2026 às 00:01**. Fim: 20/11/2026 às 22:00 (America/Sao_Paulo). Campanha, conjuntos e anúncios ATIVOS (agendados).
- Criadas com `createCampaign` (o ABO não pode ser copiado de uma referência CBO), usando como referência o conjunto
  `120253235093030163` (público Brasil 18–65, sem Advantage+, mesmas exclusões, otimização para Compra no pixel 760959141045040),
  com lance mais baixo sem limite e os 4 posicionamentos do Instagram (conferidos: nenhum foi removido).
- Os anúncios reaproveitam os criativos do lote anterior (mesma copy, link `/especialista-regularizacao/` e UTMs).
- Conjuntos: `[AUTO IG] [A+] Aberto - <criativo>`. Anúncios: `LP_2026_11_DDA_<criativo>`.

| Campanha | ID | Criativos |
|---|---|---|
| [REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-5-1] - VIDEOS A | 120253308252970163 | VID_251, 253, 255, 256, 257 |
| [REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-5-1] - VIDEOS B | 120253308267000163 | VID_258, 259, 260, 261, 262 |
| [REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-7-1] - VIDEOS C | 120253308287010163 | VID_236, 79_E, 263, 265, 265_B, 266, 266_B |
| [REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-5-1] - CARROSSEL | 120253308242550163 | CARR_64, 65, 66, 68, 69 |
| [REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-5-1] - ESTATICOS | 120253308296410163 | IMG_01, 02, 09, 10, 11 |

## Ocorrência

A primeira tentativa da campanha ESTATICOS foi enviada com início em 14/11 às 13:10, antes de o usuário corrigir o início para
15/11 às 00:01. A Meta não deixa mudar a data inicial nos 15 minutos antes do início. Por isso essa campanha
(`120253308235840163`) foi **pausada** antes de começar, renomeada para `[NAO USAR - DUPLICADA] …` e recriada com o início
correto. Ela não teve gasto e pode ser excluída no Gerenciador de Anúncios.

## Complemento (15/11/2026): campanha ABO com os 4 criativos que rodaram

Os 4 criativos que gastaram nas campanhas 1-1-1 (VID_252, VID_254, VID_264 e IMG_08) foram colocados numa campanha ABO própria,
na mesma estrutura das 5 campanhas acima: um conjunto por criativo, R$50/dia cada (**R$200/dia**), mesma referência,
público, posicionamentos (todos mantidos) e copy.

- Campanha: `[REGRA] [LP] [ABO] [COMPRA] [FRIO] [2026_11_DDA] [1-4-1] - VENCEDORES` (`120253317531880163`)
- Início: **16/11/2026 às 00:01**. Fim: 20/11/2026 às 22:00. ATIVA (agendada).
- Criativos: VID_252 (4746452325576169), VID_254 (1444127157932787), VID_264 (2419473145548928), IMG_08 (2159381978002677)
- As 4 campanhas CBO 1-1-1 originais desses criativos **continuam ativas**, por decisão do usuário. Ele decide depois se pausa.
  Enquanto as duas estruturas rodarem juntas, cada criativo concorre com ele mesmo no leilão.
