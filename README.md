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

#### Partindo do seguintes gráficos, pode-se inferir

![newplot (1)](https://user-images.githubusercontent.com/88164286/155800956-5c1c778d-d419-4484-a958-1964fc75da25.png)

- Clientes com famílias maiores (casados e com dependentes) tendem a cancelar menos
    - Será que não vale a pena dar um número de graça para o filho do cliente, pra o marido/esposa do cliente?!
  
![newplot (2)](https://user-images.githubusercontent.com/88164286/155801460-a38c4714-bb5f-4123-a886-1f818db28efc.png)
 
- MesesComoCliente baixo tem MUITO mais chance de cancelar:
    - Talvez a primeira experiência esteja sendo ruim
    - Talvez a empresa está trazendo clientes desqualificados
    - Ideia: pode ser interessante criar um programa de incentivo ao cliente nos primeiros meses?!
    
![newplot (3)](https://user-images.githubusercontent.com/88164286/155801468-abedd23e-a4c3-4f50-bc61-1f8f72ed4318.png) 

- Clientes no serviço de fibra estão cancelando muito
    - Temos que verificar o serviço de fibra, temos algum problema ali
 
![newplot (4)](https://user-images.githubusercontent.com/88164286/155801839-4f27da9d-5079-43ea-ae94-fef72cbaba48.png)

- Quase todos os cancelamentos da empresa estão no contrato mensal:
    - Plano de incentivo ao contrato anual ou 2 anos --> Dar desconto pro cara do contrato anual
   
![newplot (5)](https://user-images.githubusercontent.com/88164286/155801841-5e6cf659-5874-4537-91bf-85b4cf73a4ef.png)

- Taxa de cancelamento alta da forma de pagamento: Boleto eletrônico
    - Incentivar os clientes a mudar a forma de pagamento para cartão de crédito ou débito automático

## Para replicar este projeto

- Basta apenas fazer o download ou clonar este repositório para sua máquina e executá-lo, porém antes é importante garantir que você tenha as seguintes tecnologias no pc.

### Tecnologias utilizadas

<table>
  <tr>
    <td>Jupyter Notebook</td>
  </tr>
  <tr>
    <td>Python 3</td>
  </tr>
</table>
