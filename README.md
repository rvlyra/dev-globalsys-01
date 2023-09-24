# dev-globalsys-01


## Desafio para Géssica - Modificação dos Produtos e Cálculos

**Objetivo:** Modificar os tipos de produtos disponíveis e ajustar os valores, taxas de entrega e quaisquer outros cálculos relacionados.

**Tarefas:**

1. **Tipos de Produtos:** Modifique a lista de produtos disponíveis para representar um novo conjunto de produtos. Por exemplo, você pode escolher produtos eletrônicos, roupas ou alimentos.

**Resposta - Modificaçoes realizadas:** Os produtos escolhidos enquadram-se na categoria de moda masculina, incluindo:
-Camisa polo manga curta e manga longa 
-camisa básica 
-camisa social manga curta e longa
-calça jeans,
-calça em sarja brim 
-bermuda brim 
-jaqueta jeans
-casaco de la.

2. **Valores e Taxas:** Defina preços diferentes para os novos produtos e ajuste as taxas de entrega se necessário. Certifique-se de atualizar os valores nas funções JavaScript para calcular o custo total com base nos novos produtos e taxas de entrega.

**Resposta - Modificaçoes realizadas:** 
Os preços em reais ficaram da seguinte forma:

**Produtos**

Camisa Polo manga curta- R$60.00
Camisa Polo manga longa- R$62.00
Camisa básica - R$50.00
Camisa social manga longa - R$120.00
Camisa social manga curta - R$100.00
Calça jeans - R$104.00
Calca em sarja brim - R$122.00
Bermuda brim - R$90.00
Jaqueta jeans - R$152.00
Casaco de la - R$153.00

**Entrega**

Entrega Padrão - R$10.00
Entrega Expressa - R$15.00
Retirada na Loja - R$0.00

**Regra de Negócio**

Simples nacional: 
Taxa de 4% sobre sobre comércio com faturamento anual máximo de 180mil.

Fonte:
Tabela anexo 1 do Simples Nacional.
CNAE 4781 - 4/00
site Contabilizei: https://www.contabilizei.com.br/contabilidade-online/anexo-1-simples-nacional/

3. **Moeda Local:** Se você não está usando o Real brasileiro (R$), atualize a moeda e símbolos para refletir a moeda local usada em seu novo cenário. Por exemplo, use dólares (USD), euros (EUR) ou qualquer outra moeda.

**Resposta - Modificaçoes realizadas:** Foram adicionadas options para selecao da moeda local, inputs para selecao dos produtos e uma funçao que as atualiza o conteudo (produto, simbolo, entrega, valores) conforme o que esta contido em uma lista (podendo migrar posteriormente para uma API).

4. **Compartilhe sua versão:** Após fazer as modificações, compartilhe o código HTML e JavaScript atualizado que representa o novo cenário de produtos e cálculos.
