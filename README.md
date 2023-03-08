# Desafio Front End

# Crie uma aplicação de Login e Listagem de produtos contendo os seguintes passos:

# Tecnologias:
- Angular 
- Angular Material

# Login:

- Crie uma página de login, que tenha um formulário com e-mail e senha (com olho pra exibir o que está sendo digitado), sendo ambos obrigatórios e válidos.

- Caso o usuário insira um valor no input que não seja um e-mail, exibir uma mensagem abaixo do input que o e-mail informado não é válido.

- A senha é obrigatória, e deve ter no mínimo 6 caracteres e no máximo 10 caracteres.

- Caso o usuário insira um valor no input de senha, que não tenha os critérios mínimos, exibir uma mensagem de senha inválida.

- O botão para entrar, só deve ser habilitado após o usuário validar o formulário e deve redirecionar o usuário para a página de listagem de produtos.

# Listagem de produtos

- Crie uma tabela, que exiba id, nome, preço, quantidade, data de fabricação e data de validade de um produto. Essa tabela precisa ter a ordenação das colunas nome e preço.

- Use o array de objetos do arquivo products.json.

- Nesta tabela, crie uma coluna chamada Situação, onde exibe um texto indicando se o produto está vencido ou não.
  Ex:
  Situação: Vencido (pintar em vermelho);
  Situação: No prazo (pintar em verde).

- Nesta mesma tabela, crie um select logo acima, chamado "Situação", onde terá duas opções de filtro: vencidos e não vencidos.

# OBS:

- Visando o conceito de boas práticas de desenvolvimento, é ideal que o array de objetos de produtos tenha uma interface usando TypeScript.

- Lembrar de não renderizar elementos no DOM à toa, já que você irá trabalhar com ngIf.

- É ideal que essa aplicação seja responsiva para desktop/tablet/celular. 
  Campos para exibir no desktop:
  ID, Nome, Preço, Quantidade, Data de Fabricação, Data de Validade e Situação.
  Campos para exibir no tablet  e celular:
  ID, Nome, Preço, Quantidade, Situação.

- Fique à vontade para estruturar o layout.

