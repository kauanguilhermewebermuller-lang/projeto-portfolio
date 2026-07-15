# AGENTS — Instruções para agentes de IA

Breve: Este repositório é um projeto estático de portfólio (HTML/CSS/JS). Estas instruções ajudam agentes a serem produtivos rapidamente.

O que é importante
- Projeto simples e estático: sem build, sem testes automatizados.
- Estrutura principal:
  - `index.html`
  - `estilos/style.css`
  - `scripts/script.js`
  - `imagens/`

Conveniências e decisões relevantes
- Use HTML semântico e CSS modular em `estilos/style.css`.
- Scripts front-end leves em `scripts/script.js` — evite introduzir frameworks.
- Mantemos imagens em `imagens/` e caminhos relativos em `index.html`.

O que um agente pode fazer
- Corrigir acessibilidade básica (alt em imagens, contraste de cores).
- Melhorar estrutura semântica (usar `main`, `header`, `footer`, etc.).
- Otimizar CSS (remover regras não usadas somente quando for seguro).
- Implementar pequenas melhorias visuais seguindo a identidade existente.

Regras e limites
- Não converter o projeto para um framework (React/Vue) sem autorização.
- Evitar mudanças que alterem a estrutura de arquivos (renomear pastas) a menos que o PR explique o motivo.

Como testar localmente
- Abrir `index.html` no navegador. Para desenvolvimento rápido, um servidor estático é suficiente (e.g., `live-server`).

Padrão de PR
- Título curto e descritivo.
- Descreva mudanças de UX/CSS e inclua screenshots quando relevantes.

Links úteis
- Arquivos principais: `index.html`, `estilos/style.css`, `scripts/script.js`.

Feedback
Se quiser que eu detalhe convenções adicionais (naming, lint, CI), diga qual área focar.
