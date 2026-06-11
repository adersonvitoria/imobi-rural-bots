# A.G.A. — Robôs de Atendimento e Vendas para Imobiliária Rural

Demonstração de produto para a **A.G.A. Assessoria Imobiliária e Jurídica** (Gravataí/RS): robôs de WhatsApp para atendimento, prospecção e vendas de imóveis rurais (sítios, chácaras, terrenos, lotes e campos), com plataforma de acompanhamento.

## Páginas

| Arquivo | O que é |
|---|---|
| [`index.html`](index.html) | Plataforma com login, visão de **Diretor** (empresa inteira: KPIs, leads, equipe, financeiro) e visão de **Corretor** (carteira própria e comissões), além da tela **Testar Robô** — chat interativo num iPhone com catálogo de 8 imóveis e fotos reais |

O acesso abre direto na tela de login (`/plataforma.html` antigo redireciona para a raiz via `vercel.json`).

## Acessos de demonstração (tela de login)

| Perfil | E-mail | Senha |
|---|---|---|
| Diretor | `diretor@aga.imb.br` | `diretor123` |
| Corretor | `ricardo@aga.imb.br` | `corretor123` |

## Como rodar

Sem build e sem dependências — é HTML/CSS/JS puro (apenas Google Fonts via CDN).

```bash
# qualquer servidor estático, por exemplo:
python -m http.server 8765
# e abra http://localhost:8765
```

Ou simplesmente abra os arquivos `.html` direto no navegador.

As imagens `1.png` … `9.png` são as fotos dos imóveis usadas no chat de demonstração.
