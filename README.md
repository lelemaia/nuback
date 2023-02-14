# 
nuback

## Endpoints

- Cadastro de despesa
- Listar despesas
- Apagar despesa
- Editar despesa


###Cadastro de despesa

nubeck//api/v1/despesas

**Exemplo de Entrada**

````json
{
  valor: 100,
  categoria: 'lazer'
  conta: 'itau'
  data: '23-01-01'
  descricao: 'cinema'
}

| Campo | Obrigatório | Tipo | Descrição |
|-------:
|valor|sim|decimal| 0 valo da despesa|
|categoria| sim|texto| A categoria da despesa, 
deve ser uma categoria previamente cadastrada |
|-------------
