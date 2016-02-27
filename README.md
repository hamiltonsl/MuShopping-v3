### Alterações:
A principal alteração foi remover o requisito dos drivers ODBC (Access) de modo a facilitar a utilização do site em outras hospedagens.

Adatapção realizada no [MuShopping-v3](https://github.com/daldegam/MuShopping-v3) com permissão do autor [Leandro Daldegam](https://github.com/daldegam/).

### Instalação:
Para usar esse shopping, agora é necessária uma etapa adicional.
Criar um novo banco de dados chamado **ldShopV3** e importar o conteúdo do modules/items/items.mdb.

Para importar o banco de dados do Access:
> SQL Server Management Studio => Databases => ldShopV3 => Tasks => Import Data

Siga as instruções do assistente, não há necessidade de nenhuma outra configuração em especial.

Ao finalizar o procedimento, recomendo **deletar** o arquivo *modules/items.items.mdb*.
