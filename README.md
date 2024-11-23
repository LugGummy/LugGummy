HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div>
        <h1>Lista de Tarefas</h1>

        <div class="container">
            <input type="text" id="novaTarefa" placeholder="Adicione uma tarefa..."/>
            
            <button id="adicionar">Adicionar</button>
        </div>

        <ul id="listaTarefas">

        </ul>
    <div>

    <script src="script.js"></script>
</body>
</html>




CSS:
* {
    margin: 0;
    pad: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}


.container {
    background-color: #f4f4f9;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 350px;
}


h1{
    text-align: center;
    margin-bottom: 20px;
    color: #383838;
}

.formulario {
    display: flex;
    gap: 10px;
    margin-bottom: 20px;
}

.formulario input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ffeeee;
    border-radius: 4px;
}

.formulario button {
    padding: 10px 15px;
    background-color: aquamarine;
    border: none;
    border-radius: 4px;
    color: aliceblue;
    cursor: pointer;
}

.formulario button:hover {
    background-color: aquamarine;
}


ul{
    list-style-type: none;
}


ul li {
    padding: 10px;
    border-bottom: 1px solid #ddd;
    display: flex;
    justify-content: space-between;
    align-items: center;
}


ul li button {
    background-color: brown;
    border: none;
    padding: 5px 10px;
    color: aliceblue;
    cursor: pointer;
}


ul li button:hover {
    background-color: brown;
}
