# loja-venda-livros-cadernos
Uma loja que vende livros e cadernos - Java OOP

## Apresentação do projeto
Uma loja vende livros e cadernos. Livro tem nome e gênero. Caderno tem quantidade de materias.Ambos tem preço e uma quantidade que pode ser comprada. Os pedidos podem ou não ter um cupom de desconto aplicado ao valor total. Este cupom tem código e porcentagem de desconto. Os pedidos são de um cliente, qual tem um nome e cpf. Os pedidos pode ser só de livro, de cadernos ou ambos. Por fim, o valor do frete varia de acordo com a quantidade de cada item., seu preço e um fator a depender de seu tipo. os tipos para livro são: DRAMA, SUSPENSE e ROMANCE com os fatores 0.15, 0.10 e 0.05 respectivamente. Tal fator é multiplicativo, ao total calculado: preço * quantidade. Os tipos para caderno são: M2, M5 e M10 com os fatores 2, 5 e 10 respectivamente. tal fator é aditivo, ao total calculado: preço * quantidade.

## Modelando e Projetando
1. Identificar as entidades;
Livro, Caderno, Produto, Gênero, Matérias, Cliente, Pedido, Cupom.

2. Identificar as classes que manipulam as entidades.
3. Identificar classes utilitárias.
