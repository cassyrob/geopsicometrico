<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prueba Psicométrica</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Prueba Psicométrica</h1>
        <form id="quizForm">
            <!-- Pregunta 1 -->
            <div class="question">
                <p>1. ¿Cómo te describirías en situaciones sociales?</p>
                <label>
                    <input type="radio" name="q1" value="1"> Introvertido
                </label>
                <label>
                    <input type="radio" name="q1" value="2"> Extrovertido
                </label>
                <label>
                    <input type="radio" name="q1" value="3"> Equilibrado
                </label>
            </div>

            <!-- Pregunta 2 -->
            <div class="question">
                <p>2. ¿Cómo tomas decisiones bajo presión?</p>
                <label>
                    <input type="radio" name="q2" value="1"> Me pongo nervioso
                </label>
                <label>
                    <input type="radio" name="q2" value="2"> Me concentro y tomo decisiones rápidas
                </label>
                <label>
                    <input type="radio" name="q2" value="3"> Me tomo mi tiempo
                </label>
            </div>

            <!-- Pregunta 3 -->
            <div class="question">
                <p>3. ¿Qué tan organizado eres?</p>
                <label>
                    <input type="radio" name="q3" value="1"> Muy desorganizado
                </label>
                <label>
                    <input type="radio" name="q3" value="2"> Bastante organizado
                </label>
                <label>
                    <input type="radio" name="q3" value="3"> Muy organizado
                </label>
            </div>

            <!-- Botón para enviar -->
            <button type="button" onclick="submitQuiz()">Enviar respuestas</button>
        </form>

        <div id="result" style="display: none;">
            <h2>Resultados</h2>
            <p id="score"></p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
