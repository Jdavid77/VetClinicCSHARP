# VetClinicCSHARP

TIVE DE FAZER UPLOAD EM .RAR VISTO QUE O GITHUB NÃO ME DEIXAVA FAZER UPLOAD DA PASTA DO PROJETO

Basicamente o projeto tem 5 classes ( 6 contando com o main ): 
AnimaisdeEstimação
Cliente
Médico
Pessoa
ReceitaMédica

![image](https://user-images.githubusercontent.com/49655819/114282510-4453f400-9a3c-11eb-8e54-94555ea99c9a.png)
Menu principal da aplicação:
1- Mostra os serviços prestados na clínica
2- Permite o registo de clientes
3- Acesso ao dashboard do cliente (Após inserção de ID, dado no processo de registo)
4- Acesso ao dashboard do médico (Após inserção de ID, dado no processo de registo)
5- Acesso ao dashborad admin (basicamente o dashboard do utilizador)
6- Para sair da aplicação



![image](https://user-images.githubusercontent.com/49655819/114282880-82521780-9a3e-11eb-95cc-3cc408cece18.png)

1 - Serviços prestados na clínica


![image](https://user-images.githubusercontent.com/49655819/114282939-f2f93400-9a3e-11eb-8617-86e52e559e7b.png)

2 - Processo de registo de cliente onde é pedido o nome,morada e número de telemovel

![image](https://user-images.githubusercontent.com/49655819/114283053-ab26dc80-9a3f-11eb-82aa-b8e53350d6e0.png)

3 - Dashboard do cliente, onde é possível registar animais de estimação, editar dados do cliente, marcar consultas (indicando o id do animal que pretende ter consulta), imprimir receitas médicas e recarregar saldo.


![image](https://user-images.githubusercontent.com/49655819/114283156-37d19a80-9a40-11eb-84ac-9416a1715815.png)

4 - Dashboard do médico, onde é possível marcar turno (basicamente como é 24/7 o médico escolhe o inicio do turno e o fim), iniciar turno de emergencia de duas horas(caso não esteja em serviço) e editar dados pessoais.

![image](https://user-images.githubusercontent.com/49655819/114283197-6ea7b080-9a40-11eb-896b-fb26e3c2d860.png)

5 - Dashboard Admin, onde é possível registar um médico, mostrar todos os clientes registados na clínica, todos os médicos registados na clínica e imprimir um relatório individual de um cliente





Como funciona o processo de Consulta??

Basicamente o utilizador diz qual o animal que pretende ter consulta e de seguida indica qual o serviço que pretende.
Após isso se não houver médicos disponíveis(ou seja com turnos marcados) especializados em tal serviço o sistema não deixa prosseguir com a consulta.
Caso exista é apresentado uma lista dos médicos disponíveis para a realizaçao de tal consulta. O cliente escolhe o médico e se o turno dele coincidir com a hora atual é possível realizar a consulta. Caso a hora atual não esteja dentro do intervalo de tempo do turno do médico , o cliente tem de indicar uma hora para a nova consulta ( dentro do intervalo de tempo estipulado pelo médico ) e assim a consulta fica agendada. Após a realização da consulta o médico preescreve a receita médica para o tal animal que fica disponível para impressão no dashboard do cliente.



