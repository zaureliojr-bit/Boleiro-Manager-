# Boleiro Manager

Jogo de gerenciamento de futebol para celular, inspirado no Brasfoot. Roda direto no navegador, sem instalação e sem servidor.

## Recursos
- 8 clubes fictícios, 14 rodadas, tabela de classificação
- Partidas em dois tempos, com gols por minuto e opção de simulação rápida
- Escalação manual em 4-3-3, 4-4-2 ou 3-5-2, com postura defensiva, equilibrada ou ofensiva
- Até cinco substituições e ajuste de postura no intervalo
- Mercado de compra e venda com proteção para manter uma formação válida
- Editor de times: nomes, cores e jogadores, com importar e exportar
- Progresso salvo no próprio aparelho (localStorage)

## Publicar no Cloudflare Pages
1. Em Workers & Pages, crie um projeto e conecte este repositório.
2. Framework preset: None.
3. Build command: deixe vazio.
4. Build output directory: `/`

O arquivo `index.html` já contém todo o jogo.
