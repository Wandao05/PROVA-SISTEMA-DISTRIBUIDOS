Prova 1 de Sistemas Distribuídos

Nome: Wanderley Gonçalves
RA: 52831101840

Problema da empresa

Uma empresa precisa calcular o pagamento de horas trabalhadas. O cliente solicita ao servidor o valor correspondente a 8 horas trabalhadas, considerando uma remuneração de R$ 25 por hora.

O cálculo é realizado pelo servidor utilizando RPC.

Arquivos

servidor.py: recebe a chamada RPC e executa o cálculo.

cliente.py: solicita o cálculo ao servidor e mostra a resposta.

Resultado do teste

Ao executar o cliente, o resultado apresentado foi:

Valor do pagamento: 200

Explicação

1. Em qual programa o cálculo foi executado?

O cálculo foi executado no servidor.

2. Qual programa iniciou a solicitação?

O cliente iniciou a solicitação ao servidor.

3. O que aconteceria com o cliente se o servidor estivesse desligado?

O cliente não conseguiria realizar a chamada RPC e apresentaria um erro de conexão.
