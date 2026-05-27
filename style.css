<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia do Espaço Rural</title>
    <style>
        /* Estilos Gerais e Cores que lembram a natureza */
        :root {
            --verde-escuro: #2e7d32;
            --verde-claro: #4caf50;
            --marrom: #795548;
            --bege: #f5f5dc;
            --cinza-claro: #f9f9f9;
            --texto: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--cinza-claro);
            color: var(--texto);
            line-height: 1.6;
        }

        header {
            background-color: var(--verde-escuro);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 0.5rem 0 0 0;
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* Menu de Abas Interativas */
        .abas {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .aba-btn {
            background-color: white;
            border: 2px solid var(--verde-claro);
            color: var(--verde-escuro);
            padding: 0.8rem 2rem;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            border-radius: 30px;
            transition: all 0.3s ease;
        }

        .aba-btn.ativo, .aba-btn:hover {
            background-color: var(--verde-claro);
            color: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        /* Conteúdo das Abas */
        .conteudo-secao {
            display: none;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        .conteudo-secao.ativo {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        /* Grid de Cards de Dicas */
        .grid-dicas {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .card-dica {
            background-color: var(--cinza-claro);
            border-left: 5px solid var(--marrom);
            padding: 1.5rem;
            border-radius: 4px;
        }

        .card-dica.plantio {
            border-left-color: var(--verde-claro);
        }

        .card-dica h3 {
            margin-top: 0;
            color: var(--marrom);
        }

        .card-dica.plantio h3 {
            color: var(--verde-escuro);
        }

        /* Rodapé */
        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--marrom);
            color: white;
            margin-top: 4rem;
        }

        /* Animação simples */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <header>
        <h1>Guia do Seu Espaço Rural</h1>
        <p>Dicas práticas para cuidar da terra e dos seus animais com sustentabilidade</p>
    </header>

    <div class="container">
        
        <div class="abas">
            <button class="aba-btn ativo" onclick="abrirAba(event, 'plantio')">🌱 Guia de Plantio</button>
            <button class="aba-btn" onclick="abrirAba(event, 'animais')">🐎 Cuidado com Animais</button>
        </div>

        <div id="plantio" class="conteudo-secao ativo">
            <h2>Boas Práticas para o Cultivo e Solo</h2>
            <p>Cuidar da terra é o primeiro passo para uma colheita farta e saudável. Veja as principais recomendações:</p>
            
            <div class="grid-dicas">
                <div class="card-dica plantio">
                    <h3>1. Rotação de Culturas</h3>
                    <p>Evite plantar a mesma espécie na mesma área por várias safras seguidas. Mudar o cultivo (ex: alternar milho com feijão) quebra o ciclo de pragas e melhora os nutrientes do solo.</p>
                </div>
                <div class="card-dica plantio">
                    <h3>2. Cobertura Morta (Mulching)</h3>
                    <p>Cubra o solo ao redor das plantas com folhas secas, palha ou restos de roçagem. Isso mantém a umidade da terra, reduz a necessidade de rega e evita o crescimento de ervas daninhas.</p>
                </div>
                <div class="card-dica plantio">
                    <h3>3. Irrigação Inteligente</h3>
                    <p>Prefira sistemas de gotejamento ou regue no início da manhã ou fim da tarde. Isso evita que a água evapore rápido demais com o calor do sol.</p>
                </div>
            </div>
        </div>

        <div id="animais" class="conteudo-secao">
            <h2>Manejo e Bem-Estar Animal</h2>
            <p>Animais saudáveis produzem melhor e garantem o equilíbrio da propriedade. Foque nestes pilares:</p>
            
            <div class="grid-dicas">
                <div class="card-dica">
                    <h3>1. Água Limpa e Sombra</h3>
                    <p>Garanta que todos os piquetes e pastos tenham acesso a água fresca, limpa e áreas de sombra (árvores ou galpões) para proteger os animais do estresse térmico.</p>
                </div>
                <div class="card-dica">
                    <h3>2. Calendário Sanitário</h3>
                    <p>Mantenha as vacinas e a vermifugação rigorosamente em dia, de acordo com as regras da sua região e a espécie do animal (bovinos, equinos, aves, etc).</p>
                </div>
                <div class="card-dica">
                    <h3>3. Pastejo Rotacionado</h3>
                    <p>Divida o pasto em piquetes menores. Deixe os animais consumirem o capim em uma área e depois mude-os de lugar, dando tempo para o pasto anterior se recuperar e crescer forte novamente.</p>
                </div>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 - Guia Rural Sustentável. Cultivando um futuro melhor.</p>
    </footer>

    <script>
        // Função simples para alternar entre as abas de Plantio e Animais
        function abrirAba(evt, nomeAba) {
            // Esconde todas as seções
            const conteudos = document.getElementsByClassName("conteudo-secao");
            for (let i = 0; i < conteudos.length; i++) {
                conteudos[i].classList.remove("ativo");
            }

            // Remove a classe 'ativo' de todos os botões
            const botoes = document.getElementsByClassName("aba-btn");
            for (let i = 0; i < botoes.length; i++) {
                botoes[i].classList.remove("ativo");
            }

            // Mostra a seção atual e adiciona a classe 'ativo' ao botão clicado
            document.getElementById(nomeAba).classList.add("ativo");
            evt.currentTarget.classList.add("ativo");
        }
    </script>
</body>
</html>
