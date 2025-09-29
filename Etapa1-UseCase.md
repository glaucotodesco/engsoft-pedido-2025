# Casos de Uso do Sistema

## Atores Principais
- **Vendedor** → responsável pela interação com o cliente e criação de pedidos.  
- **Gerente do Departamento** → responsável pela gestão dos cadastros administrativos (vendedor, departamento, fornecedor, produto).  

---

## Casos de Uso

![Caso de Uso](/docs/out/docs/uml/usecase/usecase.png)


### Ator: Vendedor
1. **Cadastrar Cliente**  
   - Informar dados do cliente.  
   - Adicionar um ou mais endereços.  

2. **Manter Endereço do Cliente**  
   - Incluir, alterar ou excluir endereços do cliente.  

3. **Criar Pedido de Compra**  
   - Selecionar cliente.  
   - Definir endereço de entrega (entre os endereços cadastrados).  
   - Registrar data do pedido.  
   - Associar-se como vendedor responsável.  
   - Incluir um ou mais itens no pedido.  

4. **Gerenciar Itens do Pedido**  
   - Incluir, alterar ou remover produtos e quantidades.  

5. **Consultar Pedido de Compra**  
   - Visualizar informações completas do pedido.  

---

### Ator: Gerente do Departamento
6. **Cadastrar Vendedor**  
   - Incluir e manter dados de vendedores.  
   - Associar vendedor a um departamento.  

7. **Cadastrar Departamento**  
   - Criar e manter departamentos.  

8. **Cadastrar Produto**  
   - Registrar produtos.  
   - Associar produto a um ou mais fornecedores.  

9. **Cadastrar Fornecedor**  
   - Registrar fornecedores.  
   - Associar fornecedor a um ou mais produtos.  
