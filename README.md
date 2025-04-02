# Criterios-de-acessibilidadade
Elementos não textuais

Todas as imagens têm um texto alternativo (alt)
Todas as imagens devem ter o atributo "alt". O texto alternativo deve ser usado sempre que a imagem transmite algo relevante para o conteúdo. O texto deve ser breve e percetível. Nas imagens que não adicionam informação relevante (ex: imagem de uma bola de futebol num artigo sobre futebol), o atributo "alt" tem de existir na mesma, mas neste caso deve estar vazio, ex: alt="".  
O trabalho vai ter um atributo “alt” para o usuário identificar o que estaria no lugar da imagem caso ela nao carregue.

Os itens não textuais têm uma versão alternativa em texto
Todas as imagens, ilustrações, ou outros elementos não textuais devem ter uma forma de poderem ser lidos. Isto pode ser feito através do atributo "alt" nas imagens, mas também através de outras técnicas que permitam sempre mostrar uma versão alternativa do mesmo conteúdo. 

Sim, porque pensando nas pessoas que utilizam configuracoes assistivas para navegador pelo site. 

Não são usadas imagens que contêm blocos de texto
Nunca devem ser usadas imagens para mostrar blocos de texto. Todos os blocos de texto devem estar no formato texto e nunca dentro de uma imagem. Isto não só aumenta em várias vezes o peso da página, como torna esse conteúdo invisível para quem precisa de usar tecnologias assistivas. 

Sim para nao ficar um conteudo muito poluido visualmente.

Formulários

Todos os campos dos formulários têm uma <label> associada
Todos os campos de preenchimento (input, select, textarea, etc) têm de ter uma label associada. As labels permitem que o título do campo seja clicável, aumentando a zona clicável nas checkboxes e radio-buttons e facilitando a leitura do formulário por tecnologias assistivas (ex: screen-reader) Para associar uma label a um campo, basta corresponder o atributo "for" da label com o "id" do input, ex:
<label for="nome">Nome: </label><input id="nome" type="text" /> ou
<label>Nome: <input id="nome" type="text" /></label>  

Sim, label é essencial no campo de formulário e vai estar associada ao preenchimento dos atributos de login e cadastro.

São usados e para agrupar os vários campos nos formulários
Devem ser usados fieldsets para criar grupos de campos e organizar melhor os formulários. Cada grupo pode (e deve) ter um título, através da tag <legend>. 

Sim, utilizado para o usuario identificar as informacoes necessarias.

O envio dos formulários é feito via input/button e não através de links e JavaScript
Todos os formulários devem funcionar nativamente, ou seja, através do botão de submit. Os formulários nunca podem depender exclusivamente de JavaScript para funcionar. 

Sim, para nao utilizar os textos do formulario reenderizados em JavaScript.

Os erros nos formulários são indicados em texto e junto do campo que contém o erro
As mensagens de erro devem estar indicadas junto aos campos que contêm o erro e não apenas no topo ou no final do formulário. Isto permite contextualizar melhor os erros e ajuda a perceber onde é que os utilizadores têm de os corrigir. 
Sim, para o usuario saber onde esta o erro.

Uso da cor e elementos que piscam
Não é usada apenas a cor para transmitir informação
Nunca se deve usar apenas a cor para transmitir alguma informação. Juntamente com a cor, devem ser usados outros elementos que possam transmitir a informação pretendida. por exemplo, nas mensagens de erro, não usar a penas o vermelho. A cor deve ser acompanhada de um ícone ou outro elemento que permita reconhecer que tipo de mensagem é. 

O trabalho contém cores chamativas em todos os campos.

Não há elementos que piscam ou mudam de cores repetidamente
Não usar elementos que façam a página piscar ou mudar de cor em frequências superiores a 2Hz e inferiores a 55Hz (1Hz = 1 rotação/oscilação/imagem por segundo) Cinco por cento dos epiléticos são foto-sensíveis e podem ter ataques causados por determinadas frequências de elementos a piscar. 

O trabalho segue uma paleta unica, sem mudancas e luzes piscantes.

Navegação

São fornecidos atalhos para saltar links repetitivos
No topo das páginas deve haver um link (que pode estar escondido) que permita saltar diretamente para os conteúdos, de modo a que os utilizadores que precisem de tecnologia assistiva (ex: screen readers) não tenham que navegar por todos os links dos menus até chegarem finalmente ao conteúdo, em todas as páginas. 

Vai ser possivel acessar cada pagina atraves de links ao topo da pagina que serao de facil identificacao.

O <title> das páginas é claro, direto e percetível e está intimamente relacionado com o conteúdo da mesma
Os títulos são usados pelos motores de busca para identificar as páginas. Se houver mais do que uma página com o mesmo título as mesmas não podem ser diferenciadas uma da outra pelos utilizadores ou pela funcionalidade de Favoritos do browser. Se o utilizador adiciona uma página aos favoritos, ele não deve ter que adicionar ou alterar o título da página manualmente.
Para evitar confusões, o título da página deve ser semelhante ao título dos conteúdos existentes na página.

Sim, para facil entendimento do usuario.

O site é navegável usando apenas o teclado
A navegação com o teclado é um ponto bastante importante na acessibilidade de um website. Desta forma, não deve ser removido o outline dos links no efeito :hover. Adicionalmente, deve-se duplicar todos os efeitos do :hover também para o :focus. 

Sim, para facil uso

Semântica e Legibilidade

O conteúdo está estruturado de forma semântica
O uso de cabeçalhos (<h1>, <h2>, <h3>, ...), parágrafos (<p>) e listas (<ul>, <ol>) serve para estruturar os conteúdos na página de forma semântica e dão significado ao texto. Permite criar um nível hierárquico entre os conteúdos e que faz sentido quando lido sem estilos (CSS). A forma como os conteúdos são apresentados deve seguir uma hierarquia direta desde o item mais importante até ao item menos importante. Não podem ser saltados níveis hierárquicos. 

Sim, facil identificacao das opcões visuais na tela. 

O idioma da página está indicado no HTML 
Os screen-readers necessitam de saber em que linguagem está escrita a página para adaptarem a forma como vão ler os conteúdos. Por exemplo, se a página estiver em português e não for definido o idioma no HTML, o screen-reader vai usar um leitor inglês para ler texto em português, tornando-o impercetível. Isto é tão simples como adicionar o atributo lang="pt-PT" à tag <html> 

Sim,  para facilitar pessoas com deficiencia visua que utilizam configuracoes assistivas no seu dispositivo.

As tabelas têm headings <th> definidos
Devem ser usados cabeçalhos de linha ou de coluna para identificar claramente os conteúdos de uma tabela. Ao usar estes cabeçalhos torna-se mais fácil perceber quais são os títulos das linhas ou colunas e ajuda a perceber melhor a informação.
Para os utilizadores com screen-readers, estes cabeçalhos ajudam a adequar a forma como o texto irá ser lido (ex: título » dados) em vez de ler a tabela indiscriminadamente de esquerda para a direita ou de cima para baixo. 

Sim, para identificar os conteudos do campo.

O site funciona com as imagens desativadas
Ao desativar as imagens no browser, o site deve poder continuar a ser navegável e lido sem problemas. 

Sim, as imagens nao interferem na interface do site

O site é legível e navegável com o CSS desativado 
Ao desativar o CSS, devemos poder continuar a navegar e a ler os conteúdos do site sem problemas 

Sim, o CSS nao interefe nos atributos somente no design.

O site é legível aumentando o texto 2 vezes
Ao aumentar o texto em pelo menos 2x o site não deverá partir (os textos devem continuar a ser legíveis, e os menus navegáveis). 

Não porque as letras ja sao legiveis.
