# Treino de Matemática — Olimpíada Mirim

App de treino com 4 provas (57 questões ilustradas) no formato da 2ª fase da Olimpíada Mirim
(OBMEP, Nível 1 — 2º e 3º anos do fundamental).

- Arquivo único, sem dependências externas e sem chamadas de rede.
- Ao errar, mostra uma dica sobre aquele erro específico e permite nova tentativa.
- Progresso salvo no navegador (`localStorage`, chave `treino-mirim-v2`; a v1 é migrada para a Prova 1 e mantida como backup). Refazer uma prova nunca tira estrelas: vale o melhor resultado de cada questão.
- Ícone e modo tela cheia embutidos: no iPad, "Adicionar à Tela de Início" já vira app.

## Publicar

Basta servir `index.html` como site estático. No GitHub Pages:
Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`.
