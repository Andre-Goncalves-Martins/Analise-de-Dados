# Análise de Dados com Python

### Desafio:

Imagine que você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.

O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn(termo para dizer que o cliente cancelou o serviço da empresa) de mais de 26% dos clientes.

Isso representa uma perda de milhões para a empresa.

O que a empresa precisa fazer para resolver isso?

### Link para origem da base utilizada neste projeto
Link Original do Kaggle: https://www.kaggle.com/radmirzosimov/telecom-users-dataset

## Neste código seguimos o seguintes passos

- Passo 1: importar a base de dados para o Python
- Passo 2: Visualizar a base de dados
- Passo 3: Tratamento da base de dados
- Passo 4: Análise Exploratória -> Análise Geral -> Ver como estão os cancelamentos
- Passo 5: Olhando as colunas da base de dados  -> Identificar o motivo dos clientes cancelarem

## Após seguir estes passos foi possível concluir

- Clientes com famílias maiores (casados e com dependentes) tendem a cancelar menos
    - Será que não vale a pena dar um número de graça para o filho do cliente, pra o marido/esposa do cliente?!
    
- MesesComoCliente baixo tem MUITO mais chance de cancelar:
    - Talvez a primeira experiência esteja sendo ruim
    - Talvez a empresa está trazendo clientes desqualificados
    - Ideia: pode ser interessante criar um programa de incentivo ao cliente nos primeiros meses?!
    
- Clientes no serviço de fibra estão cancelando muito
    - Temos que verificar o serviço de fibra, temos algum problema ali
    
- Quanto mais serviços o cliente tem menor é a chance de cancelamento
    - Oportunidade: Criar um programa de incentivo a aderir outros serviços
    
- Quase todos os cancelamentos da empresa estão no contrato mensal:
    - Plano de incentivo ao contrato anual ou 2 anos --> Dar desconto pro cara do contrato anual
 
- Taxa de cancelamento alta da forma de pagamento: Boleto eletrônico
    - Incentivar os clientes a mudar a forma de pagamento para cartão de crédito ou débito automático
