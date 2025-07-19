# Flap_Bird
Jogo semelhante ao Flap Bird feito no windows forms

<p>Projeto realizado em 2022 durante o ensino técnico. O intuito foi utilizar as poucas ferramentas que o windows forms proporciona para criar algo criativo.</p>
<p></p>Para tornar esse projeto possível, utilizo a criação dinâmica de PictureBoxes para servirem como barreiras e, com o método Random, defino aleatoriamente, dentro de um escopo, a localização do espaço vazio para a passagem do jogador. Vale ressaltar que esse escopo é determinado com base na abertura da barreira anterior, o que impede a geração de passagens impossíveis. A movimentação das barreiras e a gravidade são controladas pelos ticks do Form.</p>
<p>O jogador pode fazer os pulos com as teclas: Q W E, que representam — respectivamente —pulo grande, pulo normal, pulo pequeno.</p>
