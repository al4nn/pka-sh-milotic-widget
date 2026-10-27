# Shiny Milotic — widget para OBS

1. Adicione uma fonte **Navegador** no OBS e marque **Arquivo local**.
2. Selecione o `index.html` desta pasta.
3. Configure **1735 × 280 px**: faixa de 1735 × 240 px com margem superior de 40 px.

Use **Interagir** na fonte para clicar no número e editar os brokes ou usar os botões **+1/−1**. Afaste o mouse do contador e clique fora para ocultar os controles.

O contador começa em **0**, com máxima de **9.400**, herdada do modelo do Swampert. Esses valores estão definidos por `INITIAL` e `MAXIMUM` em `assets/main.js`. A porcentagem indica progresso em relação à máxima, não probabilidade de captura.

O salvamento é automático no armazenamento local da fonte OBS, com chave exclusiva da Milotic. Não compartilha o contador do Swampert. O navegador comum tem armazenamento separado; limpar os dados pode apagar o valor. Se o armazenamento estiver bloqueado, o valor permanece apenas durante a sessão.

Arte: imagem original de `D:\pka\pokemons\350.1.png`, ícone de Água de `D:\pka\mainimages\water.png`, logo do widget de referência e fundo vetorial original de lago ao luar em `assets/images/lake.svg`. Funciona offline, sem servidor.
