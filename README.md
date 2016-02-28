### Alterações:
A principal alteração foi remover o requisito dos drivers ODBC (Access) de modo a facilitar a utilização do site em outras hospedagens.

Adatapção realizada no [MuShopping-v3](https://github.com/daldegam/MuShopping-v3) com permissão do autor [Leandro Daldegam](https://github.com/daldegam/).

----------

### Instalação:
Para usar esse shopping, agora é necessária uma etapa adicional. 

1. Criar um novo banco de dados chamado **ldShopV3**.
2. Executar o script *shopping/sql scripts/ldShopV3_SQL2005.sql*.

----------

### Opcional: Migração (Access -> SQL Server) (avançado/experimental):

Para importar o banco de dados do Access:

1. Instale o [Microsoft SQL Server Migration Assistant v6.0 for Access](https://www.microsoft.com/en-us/download/details.aspx?id=43690) (SSMA).
> Para o correto funcionamento do SSMA, é **necessária** a instalação do [Microsoft Access 2010 Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=10910) ou superior.

2. Execute o *Microsoft SQL Server Migration Assistant for Access*. 
3. Siga as instruções do assistente e selecione o arquivo *shopping/modules/items/items.mdb*.

Ao finalizar o procedimento, recomendo **deletar** o arquivo *shopping/modules/items.items.mdb*.

**Observação:** É recomendável usar o script SQL para efetuar uma instalação limpa, eu fiz alguns pequenos ajustes no banco de dados.
