<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
        <h1>Seu estilo de filme favorito é</h1>
        <script>
            //criar uma variavel
            var opcao = parseInt(prompt(`Selecione a opção desejada
            1 - Ação
            2 - Comédia
            3 - Drama
            4 - Terror
            5 - Ficção Científica
            6 - Romance`))
        switch(opcao) {
            case 1:
            document.write("É um filme de Ação")
            break;
            case 2:
            document.write("É um filme de Comédia")
            break;
            case 3:
            document.write("É um filme de Drama")
            break;
            case 4:
            document.write("É um filme de Terror")
            break;
            case 5:
            document.write("É um filme de Ficção")
            break;
            case 6:
            document.write("É um filme de Romance")
            break;
            default:
            document.write("Opção inválida")
        }
        </script>
    </center>
</body>
</html>
