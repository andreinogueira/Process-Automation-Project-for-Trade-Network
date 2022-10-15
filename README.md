# Shppings Network Process Automation

De forma geral, este projeto consiste na automação dos processos de:
  #### Cálculo de One Pages de 25 shoppings.
  #### Envio dos One Pages para o e-mail dos gerentes dos 25 shoppings.

Um One Page pode ser definido como resumo muito simples e direto, usado pela equipe de gerência de loja para saber os principais indicadores (Faturamento, Diversidade de Produtos e Ticket Médio) de cada shopping. Isto permite em 1 página (daí o nome One Page) tanto a comparação entre diferentes shoppings, quanto quais indicadores aquele shopping conseguiu cumprir naquele dia ou não.

Para fins de exemplo, foram definidas as seguintes metas (diárias e anuais) para os indicadores definidos:
 #### Faturamento:
    Meta Ano: 1.650.000
    Meta Dia: 1000
  
 #### Diversidade de Produtos (quantos produtos diferentes foram vendidos naquele período):
    Meta Ano: 120
    Meta Dia: 4
    
 #### Ticket Médio por Venda:
    Meta Ano: 500
    Meta Dia: 500

Obs: O indicador do dia deve ser o do último dia disponível na planilha de Vendas (a data mais recente).

Este projeto permite a realização automática do cálculo do OnePage de cada shopping, assim como o envio de e-mail para o gerente de cada shopping contendo o seu OnePage no corpo do e-mail, além do arquivo completo com os dados do seu respectivo shopping em anexo.

Adicionalmente, este projeto envia um e-mail para a diretoria resposnável pela rede de shoppings com 2 rankings dos shoppings em anexo. Um ranking do dia e outro ranking anual. Além disso, no corpo do e-mail, é ressaltado qual foi o melhor e o pior shopping do dia e do ano. Obs: O ranking de um shopping é dado de acordo com seu faturamento.

Por fim, as planilhas de cada shoppping são salvas dentro da pasta do shopping com a data da planilha, a fim de criar um histórico de backup.
