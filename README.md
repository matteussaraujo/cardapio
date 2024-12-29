# Lopes Burguer - Sistema de Pedido Online

Este é um sistema de pedidos online para um restaurante fictício chamado **Lopes Burguer**. O sistema permite que os usuários visualizem o menu, adicionem itens ao carrinho de compras e finalizem o pedido com a opção de enviar o pedido via WhatsApp, incluindo a entrega para um endereço.

## Funcionalidades

### 1. **Visualizar o Menu**
   - O menu exibe uma lista de itens disponíveis para compra, incluindo hambúrgueres e bebidas.
   - Cada item possui uma descrição e o preço correspondente.
   - Os usuários podem adicionar itens ao carrinho clicando no botão "Adicionar ao Carrinho" ao lado de cada item.

### 2. **Carrinho de Compras**
   - O carrinho exibe todos os itens adicionados, incluindo nome, quantidade e preço total.
   - O total do carrinho é recalculado automaticamente à medida que os itens são adicionados ou removidos.
   - Os usuários podem remover itens individualmente ou ajustar a quantidade de itens no carrinho.
   - O carrinho também mostra a quantidade total de itens e o valor total.

### 3. **Modal de Carrinho**
   - O carrinho de compras é exibido em um modal (pop-up) que pode ser acessado ao clicar no ícone do carrinho no rodapé.
   - O modal permite aos usuários visualizar, adicionar ou remover itens no carrinho.
   - Os usuários podem também finalizar o pedido diretamente do modal.

### 4. **Finalizar Pedido**
   - Ao clicar no botão "Finalizar Pedido", o sistema verifica se o restaurante está aberto (funciona entre 18h e 22h).
   - Se o restaurante estiver fechado, o sistema alerta o usuário.
   - O usuário deve preencher o campo de endereço de entrega para completar o pedido.
   - O pedido é enviado via WhatsApp para o número de telefone do restaurante, incluindo uma lista dos itens pedidos e o endereço de entrega.

### 5. **Validação de Endereço**
   - O campo de endereço de entrega é validado. Se o campo estiver vazio, o sistema alerta o usuário para preenchê-lo corretamente antes de finalizar o pedido.
   - O endereço precisa ser inserido para garantir que a entrega seja realizada corretamente.

### 6. **Indicação de Horário de Funcionamento**
   - O horário de funcionamento do restaurante é exibido na parte superior da página, com uma indicação visual colorida (verde para aberto, vermelho para fechado) de acordo com a hora atual.

## Como Usar

1. Clone ou baixe o repositório para o seu computador.
2. Abra o arquivo `index.html` em seu navegador para visualizar o sistema de pedidos online.
3. Adicione itens ao carrinho e finalize seu pedido diretamente via WhatsApp.

## Tecnologias Utilizadas

- **HTML**: Estrutura do conteúdo da página.
- **CSS**: Estilização com o framework TailwindCSS para criar uma interface responsiva e atraente.
- **JavaScript**: Lógica para gerenciar o carrinho de compras, modais, validação de dados e envio de pedidos via WhatsApp.

## Funcionalidades Futuras

- Adicionar mais formas de pagamento além do WhatsApp.
- Melhorias na interface de usuário.
- Implementação de autenticação de usuário para gerenciamento de pedidos.

## Contribuição

Se você quiser contribuir para o projeto, sinta-se à vontade para fazer um fork do repositório e enviar pull requests com melhorias.
