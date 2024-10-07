# Exibir-Elementos
### Resumo do Código: Exibir Elementos

Este projeto HTML demonstra como exibir e ocultar elementos na página usando JavaScript. Ele inclui um botão que, ao ser clicado, alterna a visibilidade de um parágrafo.

#### Funcionalidades:

1. **Interatividade com Botão**:
   - Um botão, identificado como `meuBotao`, é usado para controlar a visibilidade do texto.
   - O texto inicial, definido pelo elemento `<p>` com o ID `meuTexto`, é oculto por padrão (usando `style="display: none;"`).

2. **Manipulação do DOM**:
   - O script JavaScript obtém referências ao botão e ao texto oculto.
   - Um **event listener** é adicionado ao botão, que aguarda um clique do usuário.
   - Quando o botão é clicado, uma função verifica o estilo do texto. Se o texto estiver oculto (`display: none`), ele é exibido (`display: block`). Caso contrário, o texto é ocultado novamente.

#### Considerações:
- Este exemplo é uma boa demonstração de como usar eventos em JavaScript para interagir com o DOM, permitindo uma experiência de usuário dinâmica e interativa.
