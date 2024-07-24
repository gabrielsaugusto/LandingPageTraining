# LandingPageTraining

-Resumo e Explicação das Principais Partes
-1.Declaração de Variáveis Globais:
-As variáveis globais são definidas no :root para serem utilizadas em todo o CSS, permitindo fácil manutenção e alteração de estilos.
-2.Reset Básico:
Margens e preenchimentos são zerados para todos os elementos (\* { margin: 0; padding: 0; }) e box-sizing: border-box; é usado para incluir bordas e preenchimentos no cálculo total de largura e altura.
3.Tamanhos de Fonte e Comportamento de Rolagem:
A base do tamanho da fonte no html é definida para 10px (font-size: 62.5%;), facilitando o uso do rem.
A rolagem suave é ativada (scroll-behavior: smooth;).
4.Estilo do Corpo:
A fonte principal para o corpo do texto é definida como "Aleo" e para títulos como "Noto Sans".
5.Estilos de Títulos:
Diferentes tamanhos e transformações de texto são definidos para h1 a h6.
6.Links e Parágrafos:
Links têm a decoração de texto removida e parágrafos têm espaçamento inferior (margin-bottom: 3rem;).
7.Classes Específicas para Layout e Estilo:
.main-fund, .main-white, .main-content, .main-content2 e .section-size são usadas para manipular a aparência e disposição dos elementos nas seções.
8.Estilo do Menu:
O menu principal é fixado no topo com position: fixed;, e seu conteúdo é disposto usando flexbox.
9.Layout de Grade (Grid):
.grid-intro, .grid-p3 e outras classes relacionadas utilizam display: grid; e display: flex; para criar layouts responsivos e organizados.
10.Galeria de Imagens e Formulários de Contato:
Estilos específicos para galeria de imagens e formulários são definidos para melhorar a aparência e interação do usuário.
11.Rodapé:
O rodapé é centralizado e estilizado para links e parágrafos.
12.Menu Responsivo e Botão "Voltar ao Topo":
Classes como .close-menu, .back-to-top, e regras de mídia (@media (max-width: 800px)) são usadas para criar um layout adaptativo e responsivo para diferentes tamanhos de tela.

Classes Gerais e de Layout
1.full-width
Define um elemento para ocupar 100% da largura disponível e ser flexível dentro de um contêiner flex.
2.main-fund
Define um fundo de imagem que cobre todo o contêiner, centralizado, e define a cor do texto para branco.
3.main-white
Define o fundo branco e a cor do texto para a cor primária.
4.main-content
Define a largura máxima, centraliza o contêiner e adiciona preenchimento.
5.section-size
Define uma altura mínima de 100% da altura da viewport, garantindo que a seção ocupe a tela inteira.
Menu de Navegação
1.menu
Fixa o menu no topo da tela, com largura total e uma borda inferior.
2.menu-content
Usa flexbox para alinhar itens do menu horizontalmente e distribuir espaço entre eles.
3.menu h1
Define o tamanho e a cor do texto do título no menu.
4.menu ul
Remove os estilos de lista padrão e usa flexbox para alinhar itens.
5.menu ul li a
Define o estilo dos links no menu.
6.menu ul li a::after
Adiciona um efeito de linha animada ao passar o mouse sobre os links do menu.
7.menu-space
Cria um espaço mínimo para compensar o menu fixo.
Introdução e Seções de Conteúdo
1.grid-intro
Cria um layout de grade para a introdução com duas colunas e uma altura mínima de 100vh.
2.intro-content, .intro-img
Define um layout flexível para centralizar o conteúdo verticalmente.
3.intro-img img
Garante que as imagens se ajustem ao contêiner sem distorção.
4.jobs-content
Define o estilo e o layout para a seção de trabalhos, centralizando o conteúdo e definindo uma largura máxima.
5.grid-content-top3
Cria uma seção de conteúdo com flexbox, centralizando e ajustando-se ao conteúdo.
6.grid-content-top3-h2
Define o espaçamento inferior para o título.
7.grid-content-top3-p
Adiciona preenchimento inferior ao parágrafo.
Galeria e Conteúdo em Grade
8.grid-p3
Define uma grade com três colunas e espaçamento entre elas.
9.grid-p3 h3
Define o estilo do título dentro da grade.
10.grid-p3 h3::before
Adiciona um contador estilizado antes do título.
11.gallery-img
Define o estilo e o tamanho das imagens da galeria.
12.gallery-img img
Adiciona uma transição suave ao passar o mouse sobre a imagem.
13.gallery-img img
Define a transformação da imagem ao passar o mouse, ampliando e rotacionando.
Formulário de Contato
1.contact-form
O formulário de contato ocupa duas colunas na grade.
2.grid-form legend
Define o estilo do Legend do formulário.
3.contact-form .grid-form
Define o layout flexível do formulário com espaçamento entre os elementos.
4.group-contact
Define a flexibilidade dos grupos de contato.
5.group-contact label
Define o estilo dos rótulos dos inputs.
6.group-contact input, .group-contact-textarea
Define o estilo dos campos de entrada e textarea.
7.group-contact input,. group-contact-textarea
Adiciona uma sombra ao focar nos campos de entrada.
8.textarea-width
Define a largura e a flexibilidade do textarea.
9.group-contact button
Define o estilo do botão do formulário.
10.group-contact button
Define o estilo do botão ao passar o mouse sobre ele.
11.group-contact input::placeholder, .group-contact textarea::placeholder
Define a cor dos placeholders dos campos de entrada.
Rodapé
1.footer
Centraliza o texto do rodapé.
2.footer a
Define a cor dos links no rodapé.
3.footer p
Define o espaçamento dos parágrafos no rodapé.
Botão "Voltar ao Topo"
1.back-to-top
Define o estilo do botão "Voltar ao Topo".
Regras de Mídia
1@media (max-width: 800px)
Define estilos específicos para telas com largura máxima de 800px, ajustando o layout para dispositivos móveis.
