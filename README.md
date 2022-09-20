
<h2>Desafio Modelo Conceitual da Digital Innovation One</h2>

<h3>Objetivo:</h3>
<p>Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida:</p>

<h3>Narrativa:</h3>
<ul>
    <li> Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica;</li>
    <li> Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas;</li>
    <li> Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;</li>
    <li> A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;</li>
    <li> O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços;</li>
    <li> A mesma equipe avalia e executa os serviços;</li>
    <li> Os mecânicos possuem código, nome, endereço e especialidade;</li>
    <li> Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.</li>
</ul>

<h3>Relacionamentos:</h3>
<ul>
    <li> Um Cliente pode ter N veículos;</li>
    <li> Um Cliente pode ter N Ordens de Serviços;</li>
    <li> N Ordens de Serviços podem ter N mecânicos;</li>
    <li> N Ordens de Serviços podem ter N serviços;</li>
    <li> N Ordens de Serviços podem ter N peças;</li>
    <li> Uma ordem de serviço pode ter uma forma de pagamento;</li>
    <li> Um serviço pode ter uma tabela de preço.</li>
</ul>


<img src="https://github.com/fabio-leandro/desafio-bd-dio-oficina/blob/main/oficina.png" alt="Modelo Conceitual Oficina Mecanica"/>
