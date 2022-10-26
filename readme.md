# Criar microserviços que se relacionem 

## Objetivo
Criar um endpoint de consulta para que seja possível visualizar os dados
armazenados no banco de dados.


## Problema
Realizar uma consulta por nome da cidade e apresentar todos os clientes da cidade consultada
Seguindo a seguinte informação: consultar por nome da cidade e retornar:
{
"cidade": "Desterro",
"uf": "SC"
"clientes": [
{"id": 1, "nome": "Rodrigo"},
{"id": 2, "nome": "João"}
]
}

### A relação deve ser apenas por servço (sem relacionamento por banco de dados)
#### Tente utilizar Banco de dados diferentes