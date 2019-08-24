## Dicionários

[Python: Trabalhando com dicionários](https://www.alura.com.br/artigos/trabalhando-com-o-dicionario-no-python "Python: Trabalhando com dicionários")

[Documentação em Inglês](https://docs.python.org/3/tutorial/datastructures.html "Documentação em Inglês")

* São estruturas de dados que implementam mapeamentos

* Um mapeamento é uma coleção de associações entre  pares de valores

* O primeiro elemento do par é chamado de chave e o outro de  conteúdo

* De certa forma, um mapeamento é uma generalização da  idéia de acessar dados por índices

#### Chaves vs. Índices

* Considere que queiramos representar um caderno de telefones

* Uma solução é ter uma lista de nomes e outra de telefones

* Telefone de nome[i] armazenado em telefone[i]

* Acrescentar “Joao” com telefone “20122232”:

> nome+= “Joao” telefone+=“20122232”

* Para encontrar o telefone de “Joao”:

> Tel = telefone[nome.index[“Joao”]]

* Dicionários tornam isso mais fácil e eficiente

> telefone[“Joao”] = “20122232”
> Tel = telefone[“Joao”]
