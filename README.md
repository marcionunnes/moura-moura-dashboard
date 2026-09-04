# Moura & Moura Contadores — Painel Executivo

Site estático (HTML + CSS + JS puro, sem build step, sem backend) que lê **ao
vivo** as planilhas Google (Vendas, Clientes e Certificados Digitais) via GViz
(leitura pública, sem chave de API) e calcula os indicadores no navegador.

O painel exibe apenas **dados agregados**: totais, médias, evoluções mensais e
rankings por serviço/consultor. Nomes de clientes, CNPJs e honorários
individuais por contrato **não** são publicados neste site público, por
confidencialidade e LGPD — essa base fica só no sistema interno, com login.

Seções: vendas e receita (com carga tributária e comissões), certificado
digital (com projeção de fechamento do mês), e clientes (entradas, saídas e
composição por segmento BPO Financeiro / Assessoria Contábil). Filtros por
ano e mês recalculam tudo na hora.

🌐 Site: https://marcionunnes.github.io/moura-moura-dashboard/

## Publicar no GitHub Pages

Ação manual necessária (uma única vez): **Settings → Pages → Source: GitHub Actions**.

O deploy é automático a cada push na branch `main`, via
`.github/workflows/deploy.yml`.
