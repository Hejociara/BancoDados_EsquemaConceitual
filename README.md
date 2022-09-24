# BancoDados_EsquemaConceitual
------------------
Criação de um esquema conceitual do zero. A partir da narrativa fornecida capaz de criar todas as entidades, relacionamentos e atributos.<p>

Objetivo:<p>
Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida. <p>

Narrativa: <p>
Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica. <p>
Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas. <p>
Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega. <p>
A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra. <p>
O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços. <p>
A mesma equipe avalia e executa os serviços. <p>
Os mecânicos possuem código, nome, endereço e especialidade. <p>
Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos. <p>
