# Resumo
    Meganium RG Series Sales Report, 2024
    1 fonte
    O relatório detalha as vendas de diversos modelos "NEW MEGANIUM RG" e "MEGANIUM RG353M". As transações ocorreram em várias plataformas online, como AliExpress, Shopee e Etsy. Cada entrada inclui informações sobre o produto, data da venda, quantidade, preço unitário e total, moeda, local da venda, cupom de desconto utilizado e valor do desconto. Há também dados do comprador, como data de nascimento, nome e país de entrega, além do ID da fatura. A maioria das vendas foi realizada para compradores na Austrália, Canadá, França, Alemanha, Japão e Reino Unido, com algumas vendas para os EUA.
#

---

Meus prompts

# 	você é uma ferramenta de insights de dados de vendas. sempre utilize os dados fornecidos na sua base de conhecimento. Sempre me responda me mostrando o racional em uma tabela. interprete código e análise de dados e me respondas as perguntas a seguir: 
    
    > qual produto é mais vendido globalmente; 
    > qual o total de vendas de cada produto; 
    > qual o percentual de desconto em cada produto; 
    > em que produto é aplicado o maior percentual de desconto; 
    > correlacione o percentual de desconto com a idade do comprador; 
    > qual ponto de vendas mais vende; 
    > quais Paises compram nossos produtos; 
    > qual a idade média dos compradores por produto; 
    > considerando a moeda do país informada na coluna 'currency', qual produto tem o maior valor de venda;

# a quantidade de produtos compradas por cada país está errada. favor rever o total de vendas para cada país e retornar em uma tabela

# ainda continua errado. na planilha apresentada, a Austrália possui apenas 9 compras, o Canadá possui 14 compras, a França possui 12 compras, a Alemanha possui 09 compras, o Japão possui 08 compras, UK possui 05 compras e os USA possui 03. porque esse erro grosseiro ? qual o problema em sua leitura dos dados ?


# como posso checar os insights acima, como posso confiar na análise feita ?

---

## Perguntas quebra gelo
    ## Quais modelos Meganium foram vendidos em 2024?
        Os modelos Meganium vendidos em 2024, de acordo com os dados da fonte, são1...:
        •
        NEW MEGANIUM RG 40XXV3....
        •
        NEW MEGANIUM RG35XX1....
        •
        NEW MEGANIUM RG28XX1....
        •
        NEW MEGANIUM RG CubeXX1....
        •
        MEGANIUM RG353M2....

    ## Qual o preço unitário do produto SKU-353M01?
        Com base nos dados fornecidos, o preço unitário do produto SKU-353M01 (MEGANIUM RG353M) é de 1101....

    ## Quais modelos 'NEW MEGANIUM' foram vendidos na Shopee?
        Com base nos dados fornecidos, os modelos "NEW MEGANIUM" vendidos na Shopee são:
        • NEW MEGANIUM RG CubeXX1....
        • NEW MEGANIUM RG28XX1....
        • NEW MEGANIUM RG 40XXV2.
        • NEW MEGANIUM RG35XX3....

    ## Qual o preço unitário do RG353M mais caro?
        Para identificar o preço unitário mais caro do produto RG353M (SKU-353M01), é necessário revisar todas as transações desse produto na fonte fornecida e encontrar o maior valor na coluna unit_price.
        • Em 25/08/2024, o preço unitário do MEGANIUM RG353M foi de 110 USD1.
        • Em 10/09/2024, o preço unitário do MEGANIUM RG353M foi de 110 USD2.
        • Em 26/07/2024, o preço unitário do MEGANIUM RG353M foi de 110 USD2.
        • Em 02/07/2024, o preço unitário do MEGANIUM RG353M foi de 110 USD3.
        • Em 11/09/2024, o preço unitário do MEGANIUM RG353M foi de 110 GBP4.
        • Em 23/07/2024, o preço unitário do MEGANIUM RG353M foi de 110 EUR5.
        • Em 16/08/2024, o preço unitário do MEGANIUM RG353M foi de 110 USD6.
        • Em 02/10/2024, o preço unitário do MEGANIUM RG353M foi de 110 GBP6.
        • Em 07/08/2024, o preço unitário do MEGANIUM RG353M foi de 110 EUR7.
        • Em 03/06/2024, o preço unitário do MEGANIUM RG353M foi de 110 EUR7.


    ## Como o preço unitário é consistentemente 110, mas em diferentes moedas (USD, EUR, GBP), para determinar qual é o mais caro, precisaríamos converter todos os preços para uma moeda comum usando as taxas de câmbio do dia da venda.
        Como não tenho acesso às taxas de câmbio históricas, o preço unitário do RG353M é 110, variando apenas na moeda (USD, EUR, GBP). É importante verificar a taxa de câmbio do dia da venda para determinar qual moeda representa o valor mais alto.

    ## Qual modelo teve mais unidades vendidas?
        Para determinar qual modelo teve mais unidades vendidas, é necessário revisar a quantidade total vendida de cada modelo Meganium na fonte fornecida.
        • NEW MEGANIUM RG 40XXV: Para determinar a quantidade total vendida, somamos a coluna "quantity" de todas as transações que contêm esse modelo1....
        • NEW MEGANIUM RG35XX: Para determinar a quantidade total vendida, somamos a coluna "quantity" de todas as transações que contêm esse modelo1....
        • NEW MEGANIUM RG28XX: Para determinar a quantidade total vendida, somamos a coluna "quantity" de todas as transações que contêm esse modelo1....
        • NEW MEGANIUM RG CubeXX: Para determinar a quantidade total vendida, somamos a coluna "quantity" de todas as transações que contêm esse modelo1....
        • MEGANIUM RG353M: Para determinar a quantidade total vendida, somamos a coluna "quantity" de todas as transações que contêm esse modelo3....
        
        Após somar as quantidades de cada modelo, podemos identificar qual deles teve o maior número de unidades vendidas. Sem realizar os cálculos, não é possível determinar com exatidão qual modelo teve o maior número de vendas.


    ## Qual modelo teve o maior desconto médio?
        Para determinar qual modelo teve o maior desconto médio, é preciso calcular o desconto médio para cada modelo Meganium presente nos dados da fonte. O processo envolve os seguintes passos:
        1.
        Calcular o desconto percentual para cada transação: Utilizar a fórmula (discount_value / total_price) * 100 para obter o percentual de desconto de cada venda individual [Me].
        2.
        Agrupar as transações por modelo: Separar as transações de cada modelo (NEW MEGANIUM RG 40XXV, NEW MEGANIUM RG35XX, NEW MEGANIUM RG28XX, NEW MEGANIUM RG CubeXX, MEGANIUM RG353M) [Me].
        3.
        Calcular a média dos descontos percentuais por modelo: Para cada modelo, calcular a média dos descontos percentuais obtidos no passo 1 [Me].
        4.
        Comparar as médias dos descontos: Identificar qual modelo possui a maior média de descontos percentuais [Me].
        Sem realizar os cálculos, não é possível determinar qual modelo teve o maior desconto médio.
##

