# Teste de integração com a Google Contacts API

 - Crie uma credencial para um web server (outro), ative a People API no Google console e salve suas credenciais em um arquivo credentials.json para utilizar esse teste.

 - Após o estudo, pude observar que utilizando o parâmetro `requestSyncToken: true` e passando o `syncToken` que chega na resposta como `nextSyncToken`, podemos obter como resposta apenas os contatos modificados e ou adicionados recentemente.