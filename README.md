# PI 3 Documento de Gestão Vivo

Descrição inicial do projeto de Pi 3, 2026 para a aula de Projeto Integrador 3 semestre

Primeira entrega:
Título do Projeto;
Nome dos integrantes (com sobrenome);
Descrição do sistema que vocês querem desenvolver;
Pelo menos, 5 Personas;
Descrição das funcionalidades do sistema (tudo o que o sistema de vocês é capaz de fazer);
Definição do Escopo do projeto (o que vocês acham que conseguem entregar);
Descrição das responsabilidades de cada um no projeto, colocando o nome e quais tarefas a pessoa se responsabilizará;
Fluxo dos usuários no sistema.

## PROJECT HUB TCG


# PARTE 1: IDEIA INICIAL


## Descrição:
O mercado Pokémon tcg movimenta muita grana com produtos selados e singles, e as lojas precisam de sistemas robustos para gerenciar um inventário complexo com milhares de cartas diferentes e variações de estado de conservação. 
A ideia aqui é desenvolver  uma plataforma de e-commerce que permita aos jogadores comprar cartas específicas para seus decks e produtos fechados para colecionismo, com um sistema de carrinho de compras eficiente e controle de estoque preciso.
vamos focar em jogadores que buscam cartas específicas para torneios, colecionadores focados em expansões novas ou antigas, e presenteadores (pais e familiares).
Tecnologias: Front em Angular, back e Springboot com banco de dados em sql que simulará a jornada completa de compra, desde a vitrine até o checkout.
O foco aqui será escalabilidade. Poderemos usar sistemas como Buy List, onde o usuário pode oferecer suas cartas usadas como a Meruru (https://www.meruru.com.br/?view=ecom%2Fbuylist%2Fhome&show=2&tcg=2&fil_card=&fil_edicao=&fil_order=1&search=Filtrar)
o mercado de cartas é milhonário, e estima-se que ainda vá crescer mais até 2035 (https://www.marketgrowthreports.com/market-reports/collectible-card-game-market-102355).


## A Utopia: 
No geral, a ideia é criar uma loja virtual, focada em tcg (inicialmente pokemon), e tratá-la também como um grande forum ou rede social, incentivando clientes, usuários, intusiastas, competidores e qualquer outro perfil amante de pokémon ou do gênero tcg a interagir em uma unica plataforma.
O incentivo vem não somente de vendas, mas em número de acessos, que gera lucro com propagandas, links patrocinados e principalmente, busca por cartas que podem ser encontradas no próprio ambiente do site.
Imagine juntar toda essa galera que está espalhada em vários sites e redes sociais em um lugar só, falar de cartas raras, trocas, vendas, campeonatos, eventos e o vier à tona num so lugar. Cobrar participação de outras lojas para que tenham seu comercio em evidência num unico ambiente, onde quem está fora não é visto.
Caso possível, pensar em um ambiente marketplace, com outras lojas anunciando e vendendo no nosso site;
A ideia da escalabilidade pode levar o projeto a outros nichos como videogames, acessórios, livros, action figures... 
Mas no momento o foco será trazer um ambiente amigável para treinadores, amantes e intisuastas de pokémon tcg.

Tecnologias:
Front - Angular :/
Back - Java e Springboot
DB - SQL


## Personas:

- O competitivo (28 anos): Focado no meta (https://ptcgpocket.gg/meta/). Acessa a loja sabendo exatamente o nome da carta que precisa. Quer um sistema de busca, filtros e agilidade na entrega para torneios que podem acontecer no próximo final de semana.

- O colecionador (23 anos): Procura produtos Premium, Boces raras e cartas em estado impecável (Mint e Near Mint: https://www.ligamagic.com.br/?view=artigos/view&aid=1835). Quer imagens de alta qualidade e descrições detalhadas e precisas do estado de conservação.

- O iniciante (14 anos): Esse é o novo hobby dele. Conheceu através de um influenciador e gostou muito. Procura decks já montados (theme decks) e acessérios (shields e playmats(shields são as capas protetoras e playmats são os tapetes)). Para ele, categorias bem definidas e navegação simples.

- A mãe (45 anos): Não conhece nada, mas quer presentear o filho. Ela depende de sessões bem definidas no site como MAIS VENDIDOS, KIT PARA INICIANTES, SUGESTÃO DE PRESENTES para conseguir finalizar uma compra.

- O logista (35 anos): O adm. Precisa do backoffice para cadastrar novos produtos, alterar preços conforme o mercado flutua. Aqui o foco é administração de estoque em um painel separado.

## Fluxo do Usuário
(não entendi bem essa parte)
(em andamento)


## Escopo do Projeto
MPV
- Crud Admin: cadastro, edição e exclusão de produtos;
- vitrine e busca: página inicial com produtos e sistema de pesquisa/filtro;
- sessões bem definidas por categorias, raridades, theme decks, acessórios, etc;
- Autenticação: cadastro de cliente e login (admin e clientes com perfis diferentes);
- carrinho e checkout: adição de itens, cálculo de subtotal e finalização do pedido;
- Cálculo de frete. Quanto mais distante, mais caro. Valor de frete. Adicionado ao carrinho. (quão complexo é implementar isso ao projeto?);
- Sistema de rate, comentários e adicionar foto ao comentário;


  a pensar:

- Sistema de suporte ou criação de ticket. (o escopo geral foca só na vitrine para venda);
- Estoque para cartas soltas. Se 2 clientes querem o mesmo item e ele só tem 1 no estoque. Quem leva? (adicionar prioridade de dar baixa no estoque apenas na finalização da compra. Carrinho não garante).
- Sistema de pagamento. (verificar complexidade).
- aplicar outros idiomas ao site para escalabilidade. (Verificar complexidade e necessidade).


  para utopia (iniciar de modo simples):
- Sessão de comentários nos itens da loja (incentivar usuários a postar comentários e dar pontos de cashback. Comentários com fotos ou dando notas ganham mais(tipo a shopee que dá R$5 para quem dá nota ao um produto postando fotos));
- Sistema de rede social, com algoritmos de seguidores, like, comentários e um timeline (mais puxado para o Skoob, onde aparecem todos os usuários da comunidade, não só quem você segue);
- login separado de lojistas em caso de marketplace. (sem necessidade de aprovacao, usar politica de uso).

## Regas de Usuário
- Não é possível adicionar no carrinho mais produtos que tem no estoque; quem colocar primeiro no carrinho tem prioridade. Requisicao
- O estoque deve diminuir ao concluir uma compra;
- Qualquer pessoa pode navegar e adicionar produtos no carrinho, mas só usuários logados podem finalizar o pedido;
- O valor do carrinho deve ser alterado ao adicionar ou remover itens;
- Somente o adm pode entrar no crud e alterar informações dos produtos.

## Método Sem Corpo
(também não entendi)
(em andamenyo)


-------


# PARTE 2: REFINAMENTO

Iniciar o projeto já pensando em como vai ficar no final. Se for com cara de rede social, ja iniciar o projeto assim.
Destacar e separar os elementos que farão parte crucial do projeto.
Discutir sobre como o frete será calculado se a tela de cadastro será simples.
Pode usar APIs para certos sistemas. O professor comentou que tem api de frete que ja faz tudo sozinho.
Ao invés de um marketplace, fazer uma loja voltada para compras de usuários e revenda no site.

## MODELO: E-commerce com aspectos sociais
- Loja focada em TCG com aspectos sociais:
  Sampo de conversa (estilo reddit);
  Sistema de avaliação (nota de 0 a 10, estrelas ou etc);
  Sistema que permita postas fotos e textos para interação com outros usuários;
  Login (cliente e adm). *se for um marketplace, fazer login de logista com acesso a cadastro de itens;
  Sistema de frete (Professor orientou usar uma api com tudo pronto ao invés de programar do zero);
  Sistema de busca;
  Sessões bem definidas (promoções, ofertas, presentes, etc);
  
## PÁGINAS:
- Home
- Produtos
- Promoções
- Acessórios
- Contato

## Sessões Separadas:
- Login
- Carrinho

## Placeholder
- Imagem
- Nome
- Preço
- Descrição
- Estoque

