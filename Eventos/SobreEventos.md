- Eventos sao gatilhos disparados devido alguma interação
- A maioria dos eventos são disparados por ações do usuário.
- Normalmente executamos algum código JavaScript após um evento acontecer.
- Temos eventos de: Janela, Formulario, Teclado, Mouse, Arrasto, Transferência, Midia e outros.
- Nos atributos HTML todo evento deve ter o prefixo “on"

- Janelas
afterprint          Disparado depois da pagina ser impressa
beforeprint         Disparado antes da pagina ser impressa.
beforeunload        Disparado antes do navegador carregar outra pagina.
error               Disparado quando ocorrer um erro.
hashchange          Disparado quando o hash da url da pagina é alterado.
load                Disparado quando toda a pagina for carregada.
message             Disparado quando ocorrer uma mensagem.
offline             Disparado quando o navegador é desconectado da internet
online              Disparado quando o navegador é conectado com a internet.
pagehide            Disparado quando a pagina é ocultada.
pageshow            Disparado quando a pagina é mostrada.
popstate            Disparado quando a ocorréncia no historico do navegador é alterada.
resize              Disparado quando a janela é redimensionada.
storage             Disparado quando o armazenamento do navegador é alterado
unload              Disparado quando o usuario atualiza a pagina ou fecha a janela

- Formulário
blur                Disparado quando o foco do elemento é removido
change              Disparado quando termina de altera o valor do elemento
contextmenu         Disparado quando o usuario abre o menu de contexto.
focus               Disparado quando o elemento é focado.
input               Disparado quando o elemento recebe uma entrada de valor.
invalid             Disparado quando o valor do elemento é invalido.
reset               Disparado quando o valor do elemento é redefinido ao estado inicial.
search              Disparado quando o elemento input do tipo search é enviado.
select              Disparado quando o valor do elemento é selecionado.
submit              Disparado quando o formulario é enviado.

-Teclado
keydown             Disparado quando a tecla vai para baixo.
keypress            Disparado quando a tecla é pressionada.
keyup               Disparado quando a tecla é solta.

-Mouse
click               Disparado quando o elemento recebe um clique.
dblclick            Disparado quando o elemento recebe um clique duplo.
mousedown           Disparado quando o botao do clique vai para baixo.
mousemove           Disparado quando o cursor do mouse se move sobre o elemento.
mouseout            Disparado quando o cursor do mouse nao esta em cima do elemento.
mouseover           Disparado quando o cursor do mouse esta em cima do elemento.
mouseup             Disparado quando o botao do clique é solto.
wheel               Disparado quando a roda do mouse é rodada.
mouseenter          Disparado quando o cursor do mouse entra em cima do elemento.
mouseleave          Disparado quando o cursor do mouse sai de cima do elemento.

-Arrasto
drag                Disparado quando o elemento é arrastado.
dragend             Disparado quando o elemento para de ser arrastado.
dragenter           Disparado quando o elemento arrastado entra em um elemento que permite soltar.
dragleave           Disparado quando o elemento arrastado sai de cima de um elemento que permite soltar.
dragover            Disparado quando o elemento arrastado passa em um elemento que permite soltar.
dragstart           Disparado quando o elemento comega a ser arrastado.
drop                Disparado quando o elemento é solto.
scroll              Disparado quando o scroll é rolado.

- Transferencia
copy                Disparado quando o contetido do elemento é copiado.
cut                 Disparado quando o contelido do elemento é recortado.
paste               Disparado quando o conteudo do elemento é colado.

-Midia
abort               Disparado quando o carregamento da midia é cancelado.
canplay             Disparado quando a midia carregou o suficiente para comegar.
canplaythrough      Disparado quando a midia carregou e pode ser reproduzido até o final.
cuechange           Disparado quando o texto de uma trilha é alterado.
durationchange      Disparado quando o tamanho total da midia é alterado.
emptied             Disparado quando acontece algum problema e a midia fica indisponivel.
ended               Disparado quando a midia foi consumida até o fim.
error               Disparado quando um erro acontece.
loadeddata          Disparado quando os dados da midia sao carregados.
loadedmetadata      Disparado quando os metadados da midia sao carregados.
loadstart           Disparado quando os dados da midia comecam a ser carregados.
pause               Disparado quando a midia é pausada.
play                Disparado quando a midia é comecada.
playing             Disparado quando depois que a midia realmente comegou.
progress            Disparado enquanto o navegador obtém os dados da midia.
ratechange          Disparado quando a taxa de reproducao e aiterada.
seeked              Disparado quando a busca de dados da midia terminou.
seeking             Disparado quando a busca de dados da midia esta acontecendo.
stalled             Disparado quando o navegador nao pode buscar os dados de midia por qualquer motivo.
suspend             Disparado quando a busca de dados da midia é parado antes de ser completamente carregado.
timeupdate          Disparado quando a posicdo da reprodugéo é alterada.
volumechange        Disparado quando o volume do audio da midia é alterado.
waiting             Disparado quando a midia é pausada para armazenar mais dados em buffer.

-Outros
toggle              Disparado quando 0 usudrio abre ou fecha o elemento details.
