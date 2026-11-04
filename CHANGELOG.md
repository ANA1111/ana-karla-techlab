# Registro de evolução — Ana Karla TechLab

Este arquivo documenta as mudanças do portfólio. O histórico Git é a fonte de verdade para os commits.

## 2026-11-04 — Iteração 2
- `8021d7c` — Melhorias no jogo de memória, contagem de texto e simulação de diagnóstico.
- `0d23e77` — Estilos responsivos para métricas e apresentação alternativa quando a foto estiver ausente.
- `3033d39` — Cabeçalhos HTTP de segurança no Nginx (CSP, anti-framing, nosniff, política de permissões e referência).
- Estado: alterações enviadas ao GitHub; build, testes e atualização no Easypanel ainda precisam ser confirmados.
- Pendente: adicionar o retrato original autorizado em `public/ana-karla-hero.png`. Não substituir por imagem inventada.

## 2026-11-04 — Preparação de publicação
- `55ffb08` — Dockerfile multi-stage (Vite e Nginx).
- `4a4fe79` — Configuração de Nginx para SPA.
- `6bc7c33` — Exclusões de arquivos locais do contexto Docker.

## Práticas para próximas versões
1. Mudanças pequenas com mensagens de commit descritivas.
2. Validar `npm run build` antes de cada publicação.
3. Testar acessibilidade, responsividade e funções interativas.
4. Evitar segredos e credenciais no repositório; manter dependências atualizadas.
5. Conferir logs e respostas HTTP após cada deploy.
6. Manter a distinção entre código enviado, código testado e código publicado.
