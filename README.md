# Desafio de Projeto - Modelando um diagrama EER para um banco de dados de uma oficina

<br>

## <b>📝NARRATIVA:</b> <br>
* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica;
* Clientes levam veículos à oficina mêcanica para serem consertados ou para passarem por revisões periódicas;
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;
* O valor de cada peça também irá compor a OS;
* O cliente autoriza a execução dos serviços;
* A mesma equipe avalia e executa os serviços;
* Os mecânicos possuem código, nome, endereço e especialidade;
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos;
* Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS;
* Uma OS pode ter vários tipos  de peça e uma peça pode estar presente em mais de uma OS.

## Modificações:
* *Mecânico* e *Equipe de Mecânicos* foram separadas em entidades diferentes, podendo assim representar a recuperação do código da equipe, recuperar quantos serviços foram atribuídos a ela e representar que um mecânico pode estar em mais de uma equipe;
* *Peça* foi alocada como uma entidade.
