Para ativar o pagamento MB WAY no Shopify deverá seguir o procedimento abaixo:

1 - Criar um Pagamento Manual (Settings/Payment Providers) com a seguinte informação:

- No nome do pagamento colocar MB WAY (obrigatório)
- Nas definições adicioniais colocar o seguinte texto (recomendado):

"Pagamento por MB WAY.

Nota: Se optar por este método de pagamento deverá estar registado com o seu número de telemóvel associado ao MB WAY."

- Nas instruções do pagamento colocar o seguinte texto (recomendado):

"Por favor confirme na aplicação MB WAY o pagamento enviado."

2 - Configurar as definições de Chechout (Settings/Checkout)

- No separador Form options na opção (Shipping address phone number) escolher uma das seguintes opções (Optional ou Required). 
Nota: Se escolher Hidden o cliente não terá possibilidade de introduzir o número de telemóvel que será usado no envio do pedido de pagamento MB WAY.

- No separador Order processing, no campo Additional scripts, copiar o conteúdo do ficheiro "checkout-MBWAY-config.txt", ou "checkout-MBWAY-with-callback-config.txt", conforme pretender ou não a activação de callback, para dentro da caixa. Caso já tenha pagamentos MULTIBANCO ativo, terá que acrescentar no final do código existente.

No código existente deverá substituir a tag [MBWAYKEY] pela sua MBWAY KEY (sem os parênteses rectos) fornecida pela ifthenpay no formato AAA-000000. Poderá encontrá-la no seu contrato. Não confundir com a chave de acesso ao backoffice.





	


	
