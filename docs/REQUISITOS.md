## Requisitos
1. Cadastro do **Cliente** possui nome, número para contato, endereço, e identificador
2. **Funcionários** possuem nome, telefone, endereço e cpf
3. **Produtos** possuem preço e identificador
4. **Fornecedor** possui nome, telefone, endereço e cnpj
5. Quando o **Cliente** faz uma compra, a mesma é armazenada, contendo a data, informação do cliente, o valor total da compra, a lista dos itens vendidos e o identificador da compra
6. **Cliente** pode fazer mais de uma compra
7. **Booster** possui nome da coleção, valor e identificador
8. Clientes podem comprar ou vender cartas
9. **Cartas** vão ser dividas entre mágicas, armadilhas, monstros, e possuem: categoria, nome, descrição, possuem preço e identificador
10. **Cartas_monstro** possui atributo, tipo, nível, atk, def e efeito
11. **Cartas_mágicas** possui  tipo_magica
12. **Cartos_armadilhas**  possui tipo_armadilha
13. **Funcionários** fazem pedidos aos fornecedores
14. **Pedidos** possuem valor total, identificação do fornecedor e identificador do próprio pedido
15. Um **Deck** possui preço, tier e identificador
