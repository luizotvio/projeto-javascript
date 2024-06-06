# Projeto: Conexão de Arquivo JavaScript ao HTML

## Descrição

Este projeto tem como objetivo demonstrar a conexão entre um arquivo HTML e um arquivo JavaScript. A estrutura do projeto é composta por dois arquivos principais:

- `index.html`: Contém a estrutura padrão de um documento HTML com um título.
- `script.js`: Contém uma função JavaScript que imprime a mensagem "Conexão feita com sucesso!" três vezes no terminal do navegador.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

### index.html

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="./script.js"></script>
    <title>Conexão JavaScript e HTML</title>
</head>
<body>
    <h1>Conexão com um arquivo JavaScript</h1>
</body>
</html>
````


### script.js

```
function imprimirMensagem() {
    for (let i = 0; i < 3; i++) {
        console.log("Conexão feita com sucesso!")
    }
}

imprimirMensagem()
```

## Instruções para Rodar o Projeto

Siga as instruções abaixo para rodar o projeto e verificar se a conexão entre o HTML e o JavaScript foi bem-sucedida:

1. Clone o repositório ou faça o download dos arquivos do projeto.

2. Abra o arquivo index.html em um navegador web.
    - Você pode fazer isso de duas formas:

        - Clique duas vezes no arquivo index.html para abri-lo diretamente no navegador padrão.

        - Abra o navegador de sua preferência e arraste o arquivo index.html para a janela do navegador.

3. Abra o console do navegador para visualizar a mensagem.
    - No navegador, abra as Ferramentas de Desenvolvedor:

        - Chrome: Clique com o botão direito na página e selecione "Inspecionar" ou pressione `Ctrl+Shift+I` (Windows/Linux) ou `Cmd+Option+I` (Mac).

        - Firefox: Clique com o botão direito na página e selecione "Inspecionar Elemento" ou pressione `Ctrl+Shift+I` (Windows/Linux) ou `Cmd+Option+I` (Mac).

        - Edge: Clique com o botão direito na página e selecione "Inspecionar" ou pressione `Ctrl+Shift+I`.

        - Safari: Vá em "Preferências" > "Avançado" e marque a opção "Mostrar menu Desenvolvedor na barra de menus". Depois clique com o botão direito na página e selecione "Inspecionar Elemento" ou pressione `Cmd+Option+I`.

4. Verifique se a mensagem foi impressa três vezes no console.
    - No console do navegador, você deve ver a mensagem "Conexão feita com sucesso!" impressa três vezes, confirmando que a conexão entre o HTML e o JavaScript foi realizada com sucesso.