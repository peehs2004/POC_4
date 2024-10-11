# POC_4
# Consumo de API com fetch
O consumo de APIs usando Fetch permite que desenvolvedores façam requisições a serviços externos de forma assíncrona. Um exemplo é a integração com a API Cataas, que oferece imagens de gatos para diferentes propósitos. Ao utilizar Fetch, você pode enviar uma requisição HTTP para a API do Cataas e receber imagens ou gifs de gatos em diversos formatos e com textos personalizados. O processo é simples: Fetch faz a requisição, e a resposta é manipulada por meio de Promises, facilitando a inclusão dessas imagens dinâmicas em aplicações web.

# Funcionamento básico da API
Para o consumo de dados da API é necessário construir uma url com base na documentação da api. Neste caso, usou-se o seguinte endpoint:

/api/cats?tags=tag1,tag2&skip=0&limit=10

# Fetch

```<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>POC de Fetch Assíncrono</title>
  <!-- Link para o arquivo CSS -->
  <link rel="stylesheet" href="StylePoc4.css">
</head>
<body>
  <!-- Container para centralizar o conteúdo -->
  <div class="container">
    <h1>Exemplo de Fetch Assíncrono no JavaScript</h1>
    <button id="fetchButton">Buscar Dados</button>
    <div id="result"></div>
  </div>

  <!-- Importa o arquivo JavaScript externo -->
  <script src="ScriptPoc4.js"></script>
</body>
</html>
```

# Resultado visual
![image](https://github.com/user-attachments/assets/f42685ea-b2c8-441b-9baa-54b163e61331)

