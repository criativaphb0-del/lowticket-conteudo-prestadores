# Plano de execução — Lowticket "Vitrine Pronta"

Busca no registro externo (`npx skills find`) não retornou skills para este escopo → o plano usa as **skills já instaladas** na conta.

## Decisões tomadas (hipóteses a validar)
| Item | Decisão | Motivo |
|---|---|---|
| Perfil-alvo (beachhead) | Gestores de tráfego, social media, designers e editores | Ranking 5º/6º: dor real ("casa de ferreiro"), sem trava de conselho de classe, e a Criativa Media já fala com esse público |
| Expansão (fase 2) | Automação/IA, depois saúde regulamentada | Saúde exige compliance de conselho; vira versão separada |
| Produto | **Vitrine Pronta**: 30 dias de conteúdo de autoridade, pronto para copiar e postar | Ataca as 2 travas: tempo e bloqueio criativo |
| Tom | Resposta direta, baixo ticket (persuasivo, urgência, quebra de objeção) | Diretriz de baixo ticket |
| Preço | R$ 47 (core) · R$ 27 (order bump) · R$ 97 (upsell) | Faixa lowticket; testar 37/47/67 |

## Mapa de etapas → skills
| # | Etapa | Skill | Entrega em `produto/` |
|---|---|---|---|
| 1 | Nicho, dores e linguagem do público | `niche-research`, `deep-research` | `01-publico-dores.md` |
| 2 | Oferta, promessa, mecanismo, garantia | `copywriting` | `02-oferta.md` |
| 3 | Conteúdo do produto (30 posts/roteiros) | `post-writer`, `reels-scripting`, `hook-generator`, `content-matrix` | `03-pack-30-dias/` |
| 4 | Revisão de qualidade do pack | `post-scorer`, `post-formatter`, `marketing:brand-review` | notas de revisão |
| 5 | Lead magnet (isca) | `criador-de-lead-magnet-isca-digital` | `04-lead-magnet.md` |
| 6 | Página de vendas | `copywriting`, `marketing:content-creation` | `05-pagina-vendas.md` |
| 7 | Criativos de anúncio (Meta) | `video-ad-script-writer`, `ugc-brief-generator`, `hook-generator` | `06-criativos-meta.md` |
| 8 | Visual (capas, carrossel, thumb) | `graphic-designer`, `gemini-carousel` | `07-visual/` |
| 9 | WhatsApp de conversão + sequência de e-mail | `marketing:email-sequence`, `wc-3-conversao` | `08-whatsapp-email.md` |
| 10 | Estrutura de campanha e métricas | `marketing:campaign-plan`, `facebook-ads-account-auditor`, `marketing:performance-report` | `09-campanha-metricas.md` |

## Ordem de execução
1 → 2 → 3 (base) → 5 → 6 → 7 → 9 → 8 → 10. Cada etapa vira commit.

## Status
- [x] Pasta, pesquisa e ranking
- [ ] Etapas 1–10
