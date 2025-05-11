# DIO
Desafio E-Commerce Curso

O contexto do projeto é montar o cenário de uma operação de e-commerce contemplando a venda de produtos distintos, cada um com o seu fornecedor sendo que cada cliente gera N pedidos com N produtos. Terceiros também podem vender seus produtos na plataforma.
As formas de pagamento contemplam cartão de crédito ou PIX, sem o código verificador ficar registrado. 
Após o pedido realizado, a forma de pagamento pode ou não ser aprovada, e, mesmo depois de aprovada esta pode ser cancelada antes de atingir o status de entrega iniciada. Neste caso, tanto o valor como o frete são estornados.
Feito o pedido, é gerado um código e, uma vez dada início a entrega, é gerado um código de rastreio ligado ao API dos correios onde o cliente pode acompanhar a entrega.
