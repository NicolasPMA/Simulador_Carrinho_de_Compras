# 🛒 Simulador de Carrinho de Compras
Este é um código feito para implementar os conceitos estudados de Orientação a Objetos.

## 🚀 Funcionalidade
- Adiciona itens de um estoque já definido ao carrinho.
- Imprime quais itens estão no carrinho e a quantidade respectiva de cada um. Após isso, imprime o valor total do carrinho.

## 💻 Tecnologia utilizada
- C++: Linguagem de programação principal.

## 💡 Como funciona
Quando rodar o código, o estoque de produtos será exibido junto ao menu de opções.

Menu:
1. Adicionar item ao carrinho
- O usuário deve fornecer o nome do produto, em estoque, que deseja adicionar ao carrinho.
- Após fornecer o nome do produto desejado, o usuário deve fornecer quantas unidades desse produto deseja.
2. Ver total do carrinho
- Todos os itens presentes no carrinho são mostrados para o usuário. assim como o valor total no carrinho.
3. Finalizar compra e sair
- Finaliza a compra e encerra a execução do código.

## ⚙ Como o código funciona

O código é feito a partir dos conceitos de orientação a objetos. As classes são criadas juntas ao seus construtores para serem utilizados na main.
São feitos alguns tratamentos para evitar possíveis erros de entrada.
Os produtos em estoque podem ser adicionados e alterados na main utilizando os construtores da classe EstoqueProdutos.
- "estoque.adicionaProduto(ProdutoEstoque("monitor", 700, 100));"

Conceitos utilizados:
- Conceitos gerais de OO.
