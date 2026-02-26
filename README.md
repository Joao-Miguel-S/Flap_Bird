# Flap Bird

![Badge](https://img.shields.io/badge/C%23%20/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)


## Sobre o projeto

<p>Em 2022, durante o ensino técnico, decidi utilizar as poucas ferramentas que o windows forms proporciona para criar algo criativo, assim nasceu o Flap Bird em C#.</p>

<p>Para tornar esse projeto possível, utilizo a criação dinâmica de PictureBoxes para servirem como barreiras e, com o método Random, defino aleatoriamente dentro de um escopo a localização do espaço vazio para a passagem do jogador. Vale ressaltar que esse espaço é determinado com base na abertura da barreira anterior, o que impede a geração de passagens impossíveis. A movimentação das barreiras e a gravidade são controladas pelos ticks do Form.</p>

## Gameplay

<p>O jogador pode fazer os pulos com as teclas: Q W E, que representam respectivamente: pulo grande, pulo normal e pulo pequeno. A cada 5 pontos que o usuário alcança, a velocidade do jogo aumenta.</p>
