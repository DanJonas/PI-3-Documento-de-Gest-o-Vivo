# PI 3 Documento de Gestão Vivo

Descrição inicial do projeto de Pi 3, 2026 para a aula de Projeto Integrador 3 semestre


## PROJECT HUB TCG


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
- Autenticação: cadastro de cliente e login (admin e clientes com perfis diferentes);
- carrinho e checkout: adição de itens, cálculo de subtotal e finalização do pedido;

## Regas de Usuário
- Não é possível adicionar no carrinho mais produtos que tem no estoque;
- O estoque deve diminuir ao concluir uma compra;
- Qualquer pessoa pode navegar e adicionar produtos no carrinho, mas só usuários logados podem finalizar o pedido;
- O valor do carrinho deve ser alterado ao adicionar ou remover itens;
- Somente o adm pode entrar no crud e alterar informações dos produtos.

## Método Sem Corpo
(também não entendi)
(em andamenyo)