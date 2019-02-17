<h1>Treino com API do Uber</h1>

Eu uso o GitHub para armazenar os códigos de projetos que eu faço. Nesse repositório você encontra exercícios que eu já fiz para treinar raspagem de dados com a API do Uber.

Para acessar a API, usei minhas credenciais em um arquivo separado que não subi para o repositório. Para definir as credenciais, rode o seguinte o código antes:</b>

<pre><code>import json<br>
uber_credentials = {}<br>
uber_credentials['server_token'] = 'SEU SERVER TOKEN VAI AQUI'<br>
with open('credenciais_uber.json', 'w') as secret_info:<br>
  json.dump(uber_credentials, secret_info, indent=4, sort_keys=True)<br></code></pre>
