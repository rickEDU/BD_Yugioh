## Modelo Relacional

Cliente(<ins>id_cliente</ins>, endereco, contato, nome)<br>
Compra(<ins>id_compra</ins>, **id_cliente**, data)<br>
Item_compra(<ins>id_produto_c</ins>, **id_compra**, quantidade, preco)<br>
Produto(<ins>id_produto</ins>, **id_cliente**, preco, qtd_estoque, descricao)<br>
Carta(<ins>id_produto</ins>, nome, categoria)<br>
Carta_monstro(<ins>id_produto</ins>, tipo, nivel, efeito, def, atk, atributo)<br>
Carta_armadilha(<ins>id_produto</ins>, tipo_armadilha)<br>
Carta_magica(<ins>id_produto</ins>, tipo_magica)<br>
Booster(<ins>id_produto</ins>, nome, colecao, descricao)<br>
Deck(<ins>id_produto</ins>, nome, tier, descricao)<br>
Fornecedor(<ins>cnpj</ins>, endereco, nome, telefone)<br>
Pedido(<ins>id_pedido</ins>, **cpf_funcionario**, **cnpj_fornecedor**, valor_total)<br>
Funcionario(<ins>cpf</ins>, endereco, telefone, nome)<br>
Item_compra_produto(<ins>**id_produto_c**<ins>, <ins>**id_produto**<ins>)<br>
Produto_pedido(<ins>**id_produto**<ins>, <ins>**id_pedido**<ins>)<br>