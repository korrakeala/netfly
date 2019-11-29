# netfly
repo para probar Heroku con MongoDB

Instrucciones de ejecución:
- Si se desea consumir API para envío de mails: Obtener una API Key de Mailgun. Clonar el repositorio. En src>main>resources>application.properties poner emailSettings.enabled en true y llenar los demás datos de Mailgun.
- En src>main>resources>Netfly.postman_collection.json se encuentran los HTTP methods para hacer las requests, nosotras usamos Postman.
- El proyecto está deployado en Heroku (sin envío de mails). Para obtener el link, ponete en contacto conmigo.