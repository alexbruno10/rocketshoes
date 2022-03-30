# :rocket: Rocketshoes - Ignite

---

O objetivo era criar um projeto de carrinho de compras, no qual, o cliente poderia adicionar o produto ao carrinho, e adicionar a quantidade, respeito o estoque do produto.

Foi utilizado o localStorage para realizar testes, juntamente com o JSON Server.

:arrow_forward: A page Home, trás o layout principal da página, com as informações dos produtos, como preço e descrição, juntamente com o botão de adicionar ao carrinho e o component Header;

:arrow_forward: O component Header da aplicação, trás o botão do carrinho, no top da tela, no qual mostra a quantidade de produtos no carrinho e quando acionado, é redirecionado para a página Index do Cart;

:arrow_forward: A page Cart, trás o layout do carrinho, no qual é possível adicionar mais quantidade do produto, e remover o produto do carrinho. É apresentado também o subtotal e o total dos produtos;

:arrow_forward: O hook useCart é o caração da aplicação, ele é responsável pelas funções addProduct, removeProduct e updateProductAmount, juntamente com o useState de cart;
