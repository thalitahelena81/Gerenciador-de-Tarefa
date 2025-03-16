# Gerenciador-de-Tarefa
Gerenciador de Tarefa Simples
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerenciador de Tarefas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Gerenciador de Tarefas</h1>
        <form id="task-form">
            <input type="text" id="task-input" placeholder="Adicionar nova tarefa..." required>
            <button type="submit">Adicionar</button>
        </form>
        <ul id="task-list"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
