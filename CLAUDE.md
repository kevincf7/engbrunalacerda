# engbrunalacerda — campanhas, ideias e criativos

Este repositório centraliza tudo sobre **subir e otimizar campanhas** (Meta Ads e Google Ads,
via OneClick Ads), as ideias de campanha e os criativos usados nelas.

Não coloque aqui:
- vídeos do @manualdetudobr → repositório `videos-remotion`
- o app Prato Forte → repositório `prato-forte`
- o negócio de criação de sites → repositório `orbitatech`

## Estrutura

- `campanhas/` — um arquivo por campanha subida (`AAAA-MM-DD-nome.md`): conta, objetivo,
  orçamento, conjuntos, anúncios, posicionamentos e o que foi decidido.
- `ideias/` — ideias de campanha, ângulos, ganchos e públicos para testar.
- `criativos/` — briefings e roteiros de criativos (arquivos de vídeo grandes ficam fora do git).
- `relatorios/` — análises de resultado e aprendizados.

Ao terminar de criar ou alterar uma campanha, registre o que foi feito em `campanhas/`.

## Regras para criação de campanhas Meta Ads

### Posicionamentos de vídeo

- Vídeos verticais (9:16) **também rodam no Feed e no Perfil do Instagram**. Nunca remova
  `instagram:stream` nem `instagram:profile_feed` por causa do formato do vídeo.
- Ao criar campanhas com vídeo (copyReferenceCampaign / createCampaign / createAdsInAdSet),
  use os posicionamentos `instagram:stream`, `instagram:profile_feed`, `instagram:reels` e
  `instagram:story`, a menos que o usuário peça outra coisa.
- A ferramenta OneClick remove sozinha os posicionamentos de Feed quando o vídeo é vertical
  (`placementNarrowing` no resultado do worker). Depois que o job terminar, confira os
  posicionamentos de cada conjunto e, se Feed/Perfil tiverem sido removidos, recoloque-os com
  `updateAdSet` (`placements`: os 4 acima) sem perguntar.
- O mesmo vale para carrosséis e imagens: a ferramenta pode remover Reels/Stories. Se o
  usuário ou a campanha de referência usa os 4 posicionamentos do Instagram, recoloque-os
  depois que o job terminar.
