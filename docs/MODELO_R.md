## Modelo Relacional

Cliente(<ins>id_cliente</ins>, endereço, contato, nome)<br>
Compra(<ins>id_compra</ins>, itens_vendidos, valor_total_compra, inf_cliente, data)<br>
Item_compra()<br>
Produto(<ins>id_produto</ins>, preço, qtd_estoque)<br>
Carta(<ins>id_produto</ins>, descriçao, nome, categoria)<br>
Carta_monstro(<ins>id_produto</ins>, tipo, nivel, efeito, def, atk, atributo)<br>
Carta_armadilha(<ins>id_produto</ins>, tipo)<br>
Carta_mágica(<ins>id_produto</ins>, tipo)<br>
Booster(<ins>id_produto</ins>, descricao, coleçao, nome)<br>
Deck(<ins>id_produto</ins>, nome, tier, descriçao)<br>
Fornecedores(<ins>cnpj</ins>, endereco, telefone, nome)<br>
Produto_pedido(<ins>id_pedido</ins>, valor_total, qtd_produtos)<br>
Funcionário(<ins>cpf</ins>, endereco, telefone, nome)<br>