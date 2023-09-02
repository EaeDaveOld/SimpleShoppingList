# SimpleShoppingList
O algoritmo foi escrito para ser um gerenciador de tarefas básico, mais especificamente uma lista de compras. <br>
Onde é possível: <br>

<ul>
  <li>Adicionar itens</li>
  <li>Remover itens</li>
  <li>Modificar itens</li>
</ul>

Todos os dados são persistidos enquanto o programa estiver rodando, ou no loop, já que os mesmos são armazenados em variáveis e não consultam nenhum banco de dados. </br>
Não possui interface gráfica, então toda interação é feita pelo terminal do sistema operacional.

Se o seu sistema for MacOs ou Linux, substitua a variável "limpar_console = os.system('cls')" para "limpar_console = os.system('clear')".

## Usando o poetry

#### Rode o comando `poetry shell`
#### Rode o comando `poetry install`
#### Execute o projeto com `python3 lista_compras.py`
