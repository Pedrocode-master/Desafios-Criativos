# Desafios-Criativos


Atue como um especialista em N8N.

Crie uma automação para acompanhar automaticamente tarefas pendentes de uma equipe, identificando tarefas próximas do vencimento ou atrasadas e notificando os respectivos responsáveis.

Público:
Equipe de melhoria contínua e responsáveis pelas tarefas.

Ferramentas envolvidas:
N8N, Google Sheets e Gmail.

Fluxo:

1. Consultar diariamente uma planilha contendo as tarefas da equipe.
2. Identificar as tarefas que estão próximas do vencimento ou que já estão atrasadas.
3. Verificar se cada tarefa possui um responsável e um endereço de e-mail válido.
4. Percorrer as tarefas identificadas individualmente.
5. Enviar um e-mail personalizado ao responsável, informando a tarefa, o prazo e seu status.
6. Atualizar a planilha após o envio, registrando que a notificação foi realizada.

Regras:
Ignorar tarefas sem responsável ou sem endereço de e-mail válido.
Não enviar mais de uma notificação para a mesma tarefa no mesmo dia.
Enviar uma mensagem diferente para tarefas atrasadas e tarefas próximas do vencimento.
Não enviar notificações para tarefas que estejam dentro do prazo e não estejam próximas do vencimento.
Registrar na planilha o envio da notificação para permitir o controle e evitar duplicidades.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
