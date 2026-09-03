# Moura & Moura Contadores — Painel Executivo

Site estático (HTML + CSS puro, sem build step, sem backend) com os indicadores
consolidados de vendas, honorários, base de clientes e certificados digitais da
Moura & Moura Contadores.

O painel exibe apenas **dados agregados** (totais, médias e distribuições).
Registros individuais de clientes (nomes, CNPJs, honorários por contrato) não
são publicados neste site público, por confidencialidade e LGPD.

🌐 Site: https://marcionunnes.github.io/moura-moura-dashboard/

## Publicar no GitHub Pages

Ação manual necessária (uma única vez): **Settings → Pages → Source: GitHub Actions**.

O deploy é automático a cada push na branch `main`, via
`.github/workflows/deploy.yml`.
