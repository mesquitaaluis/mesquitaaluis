<!DOCTYPE html>
<html>
<head>
    <title>Respostas <Divertidas class="html"></Divertidas></title>
    <style>
        .resposta {
            font-size: 24px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <h1>Você é a Maria Clara?</h1>
    <button onclick="responderSim()">Sim</button>
    <button onclick="responderNao()">Não</button>
    
    <div class="resposta" id="respostaDiv"></div>
    
    <script>
        function responderSim() {
            var respostaDiv = document.getElementById('respostaDiv');
            respostaDiv.innerHTML = 'Pé de prancha';
        }
        
        function responderNao() {
            var respostaDiv = document.getElementById('respostaDiv');
            respostaDiv.innerHTML = 'Pé de neném';
        }
    </script>
</body>
</html>
