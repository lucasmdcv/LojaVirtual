Loja Virtual Básica
Este projeto é uma loja virtual simplificada desenvolvida do zero para demonstrar a criação de um e-commerce funcional utilizando apenas tecnologias front-end: HTML para a estrutura, CSS (com Tailwind CSS) para estilização e JavaScript para toda a lógica interativa.



 ![Screenshot_1](https://github.com/user-attachments/assets/e6dac1de-3852-40ea-8d1a-39622b936a8a)




Funcionalidades Principais
Listagem de Produtos: Exibe produtos com suas descrições detalhadas, imagens e preços.

Produtos em Destaque: Uma seção dedicada a produtos selecionados para maior visibilidade.

Filtro por Categoria: Navegue facilmente pelos produtos utilizando filtros por categoria.

Carrinho de Compras Interativo:

Adicione e remova itens.

Ajuste a quantidade de produtos diretamente no carrinho.

Visualização clara do subtotal e total da compra.

Persistência de Dados: O carrinho salva os itens mesmo que o navegador seja fechado, utilizando Firebase Firestore para um ambiente robusto e multiusuário, com um fallback para localStorage caso a conexão com o Firebase não esteja disponível.

Avaliações de Clientes: Cada produto pode exibir avaliações simuladas, incluindo estrelas e comentários, oferecendo uma visão rápida da satisfação do cliente.

Design Responsivo: A loja se adapta perfeitamente a diferentes tamanhos de tela, desde desktops até dispositivos móveis, garantindo uma boa experiência de usuário em qualquer aparelho.

Tecnologias Utilizadas
HTML5: Estrutura semântica da página.

CSS3: Estilização e layout, com o auxílio do Tailwind CSS para agilizar o desenvolvimento e garantir a responsividade.

JavaScript (ES6+): Lógica do carrinho, gerenciamento de produtos, filtros e interação com o usuário.

Firebase SDK:

Authentication (Anônima): Para gerar um ID de usuário único e persistente.

Firestore: Banco de dados NoSQL para armazenar e sincronizar os dados do carrinho em tempo real.

Como Rodar o Projeto
É muito simples colocar a loja para funcionar:

Clone o Repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

Abra o Arquivo: Simplesmente abra o arquivo index.html no seu navegador web preferido.

A loja será carregada diretamente, e você poderá começar a explorar e adicionar produtos ao carrinho!

Estrutura do Projeto


acesse o site : 

.
├── index.html
├── README.md
└── (outros arquivos, se houver: ex: /css, /js, /img)

index.html: Contém toda a estrutura HTML, CSS embutido (via CDN do Tailwind) e o código JavaScript (também embutido para simplicidade).

Contribuição
Sinta-se à vontade para explorar, usar e aprimorar este projeto. Sugestões e contribuições são sempre bem-vindas!
