MANAGER FC V8
===============
PWA de jogo de gerenciamento de futebol.

Recursos principais:
- 20 clubes e 38 rodadas.
- Calendário fixo de turno e returno: cada clube enfrenta os demais duas vezes.
- Em cada rodada os 20 clubes jogam; a classificação é atualizada com os 10 jogos.
- Tabela começa zerada e os resultados já disputados ficam persistidos.
- 3 partidas por mês de janeiro a outubro e 4 em novembro/dezembro.
- Avanço de dias manual.
- Decisão obrigatória a cada 3 dias: 10 decisões por mês.
- Painéis de opinião: Diretoria, Comissão Técnica, Torcida, Capitão e Financeiro.
- Janela de transferências em janeiro, fevereiro, julho, agosto e setembro.
- Fim de temporada após a 38ª rodada.
- Salvamento independente por sessão/aba via sessionStorage.
- Funciona como PWA após ser servido por HTTP(S).

Como usar:
1. Extraia o ZIP.
2. Para testar no computador, use um servidor local, por exemplo:
   python -m http.server 8000
3. Abra http://localhost:8000/
4. No Chrome/Chromebook, use a opção de instalar o app quando disponível.

Arquivos:
index.html
manifest.json
sw.js
icon-192.svg
icon-512.svg
README.txt
