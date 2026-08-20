# MengãoShops

Página fictícia de uma loja não oficial de produtos do Clube de Regatas do Flamengo, desenvolvida com HTML5 e CSS3.

## Tema da página

A página apresenta a "MengãoShops", uma loja não oficial voltada para torcedores do Flamengo.

## Cores escolhidas

Um vermelho bem escuro, usado como cor de fundo do body.
Vermelho escuro, usado na borda inferior do cabeçalho topo.
Uma cor terracota avermelhado, cor de fundo da seção "Sobre".
Um salmão mais claro, cor de fundo da seção "Produtos".
Rosa salmão claro, cor de fundo da seção "Contato".
Um tom de vermelho vivo, usado no destaque do título da seção "Sobre".
Um marrom escuro, usado no texto de parágrafos e tags.
Preto, usado em títulos h2 e no botão de contato.
Antiquewhite — um tom de branco que gosto de usar, que aprendi na oficina, usados em fundos de tags, cards e bordas.
A paleta segue o vermelho, branco e preto em referência às cores do Flamengo.

## Seletores utilizados

*
html, body, p
.topo, .topo-conteudo, .sobre, .sobre-tag, .sobre-img, .produtos, .produtos-card, .produtos-cards, .contato, .contato-botao
.menu-links a, .sobre h2, .sobre p, .produtos h2, .produtos p, .produtos card, .contato h2, .contato-texto , .contato-card 


## Onde foram aplicados margin, padding e border

Margin: usado para espaçar elementos entre si, como em .menu-links, nas tags .sobre-tag, .produtos-tag, .contato-tag com margin-bottom e margin-left e nos títulos (h2 de cada seção) para separá-los do conteúdo abaixo.
Padding: usado dentro dos elementos para dar espaço interno, como nas seções (.topo, .sobre, .produtos, .contato com padding: 80px 0 ou 20px), nas tags de texto (padding: 8px 14px), nos cards de produto .produtos-card com padding: 28px e no botão de contato (.contato-botao com padding: 14px 24px).
Border: usada para criar contornos e destaques, como a borda inferior do cabeçalho (.topo com border-bottom), as bordas arredondadas das tags e do card de produto (border, combinado com border-radius), e a borda ao redor das imagens/cards.

## Como o box model foi utilizado

Logo no início do CSS foi aplicado um reset com o seletor "*", zerando o margin, padding e definindo o box-sizing: border-box para todos os elementos.
Escrevendo box-sizing, o padding e a border passam a ser incluídos dentro da largura e altura definidas para o elemento, evitando que o tamanho "estoure" o layout — isso é visível em elementos como .produtos-card, e nas tags .sobre-tag, .produtos-tag e o .contato-tag.
As imagens também reforçam o uso do box-sizing, garantindo que border-radius e dimensões fiquem do jeito que eu escolhi na caixa do elemento.

## Dificuldade encontrada e como foi resolvida

Uma dificuldade encontrada: Foi alinhar e centralizar elementos (como o título e a imagem da seção "Sobre"), o que levou ao uso de valores fixos de margin-left. 
Como foi resolvido o problema: Foi contornado ajustando manualmente os valores de margin até o resultado visual ficar centralizado na tela de teste.