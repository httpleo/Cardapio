PROJETO ![Screenshot_1](https://github.com/httpleo/Cardapio/assets/151533709/90465665-0196-45f3-bf0d-498405e742dc)


# Dev Burguer

Dev Burguer é uma aplicação de um site para uma hamburgueria fictícia. A aplicação permite que os usuários visualizem o menu, adicionem itens ao carrinho, e façam pedidos. Este projeto utiliza HTML, CSS, e JavaScript.

## Visão Geral

- **Nome do Projeto**: Dev Burguer
- **Descrição**: Um site para uma hamburgueria fictícia que permite que os usuários visualizem o menu, adicionem itens ao carrinho e façam pedidos.
- **Tecnologias Utilizadas**: HTML, CSS (TailwindCSS), JavaScript

## Funcionalidades

- Visualização do menu de hambúrgueres e bebidas.
- Adição de itens ao carrinho de compras.
- Remoção de itens do carrinho de compras.
- Cálculo do total do carrinho.
- Finalização do pedido com inserção do endereço de entrega.

## Estrutura do Projeto

DevBurguer/
├── assets/
│ ├── hamb-1.png
│ ├── hamb-2.png
│ ├── hamb-3.png
│ ├── hamb-4.png
│ ├── refri-1.png
│ ├── refri-2.png
├── css/
│ ├── output.css
├── index.html
├── script.js
└── README.md

## Como Executar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/httpleo/Cardapio
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd cardapio
    ```

3. Abra o arquivo `index.html` no seu navegador preferido.

## Detalhes do Código

### HTML

O arquivo `index.html` contém a estrutura básica do site, incluindo o cabeçalho, menu e modal do carrinho.

### CSS

O arquivo `output.css` contém os estilos personalizados usando TailwindCSS. Além disso, são importadas fontes do Google Fonts e ícones do Font Awesome.

### JavaScript

O arquivo `script.js` contém a lógica principal para adicionar itens ao carrinho, remover itens, atualizar o total do carrinho e manipular o modal do carrinho.

### Funcionalidades JavaScript

- **Abrir o Modal do Carrinho**: Quando o usuário clica no botão do carrinho.
- **Fechar o Modal do Carrinho**: Quando o usuário clica fora do modal ou no botão de fechar.
- **Adicionar ao Carrinho**: Quando o usuário clica no botão de adicionar ao carrinho para um item específico.
- **Remover do Carrinho**: Quando o usuário clica no botão de remover no modal do carrinho.
- **Atualizar o Modal do Carrinho**: Atualiza a lista de itens e o total do carrinho no modal.
- **Verificar Endereço**: Verifica se o campo de endereço está preenchido ao finalizar o pedido.
- **Verificar Horário de Funcionamento**: Mostra se o restaurante está aberto ou fechado com base no horário atual.

## Exemplo de Uso

Para adicionar um item ao carrinho, clique no botão de carrinho ao lado do item desejado. O total do carrinho será atualizado automaticamente. Para remover um item, abra o carrinho, e clique no botão "Remover" ao lado do item que deseja remover. Insira seu endereço e finalize o pedido clicando em "Finalizar pedido".

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.

- **Email**: drleonardobarreto96@gmail.com
- **GitHub**: [seu-usuario](https://github.com/httpleo)
