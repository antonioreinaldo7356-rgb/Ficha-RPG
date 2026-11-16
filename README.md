# Sylvarion — Ficha de RPG (PWA)

Ficha do Assassino Verde (D&D 5E) instalável no celular, funciona offline e salva na nuvem (Supabase).

- `public/` — o app (HTML + CSS compilado + fontes locais + service worker + manifest)
- Hospedagem: Vercel (deploy automático a cada push na `main`)
- Nuvem: Supabase, tabela `character_sheets` acessada só por RPC (`get_sheet`/`save_sheet`) com código secreto
