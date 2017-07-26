# yii2
cruDesenvolva uma API Rest para um sistema gerenciador de tarefas (inclusão/alteração/exclusão). As tarefas consistem em título e descrição, podendo ser ordenadas por prioridade.

Dentro do pasta dump tem o dump da base de dados

para retornar API REST

para retornar todos os registros de tarefas
metodo GET
Acessar http://localhost/basic/web/api/default

para acessar um unico registro
metodo GET
id = int
http://localhost/basic/web/api/default/id

para criar registro via api
http://localhost/basic/web/api/default/create
metodo POST
parametros
titulo (string)
descricao (string)
prioridade_id(int) (1(baixa),2(media) ou 3(alta))


para alterar registro via api
id = int

Selcione a aba body e a opção x-www-form-urlencoded
http://localhost/basic/web/api/default/id
metodo PUT
parametros
titulo (string)
descricao (string)
prioridade_id(int) (1(baixa),2(media) ou 3(alta))

para apagar registro via api
id = int
http://localhost/basic/web/api/default/id
metodo DELETE
