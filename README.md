# MuambaBot
*Robo do telegram de notificação de status de encomendas nos correios.*

## Partes da Aplicação

1. Cliente - NodeJs:
*Responsável por Enviar e Receber do Telegram*

2. API RESTFul - NodeJs:
*Responsável por Sincronizar com os correios, tratar recebimento e retorno das informações.*

## Atividades Implementadas:
#### Cliente:
- [] Criar Estrutura Cliente NodeJs + Telegraf
- [] Receber Código dos correios do usuário;
- [] Tratar Código Recebido;
- [] Enviar código para a WebApi;
- [] Receber Resposta da WebApi;
- [] Tratar Código Recebido da WebApi;
- [] Retornar Informação para usúario;
- [] Criar estrutura MongoDB;
- [] Armazenar código de um usuário;
- [] Rotina para Verificar Mudança de Status de um item;
- [] Informar Usuário automaticamente quando mudar status;

#### API:
*Arquitetando Solução*
