# projetos.alura.arthur.1D
repositório de atividades da disciplina educação digital 
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Grimório do Aventureiro | Portfólio RPG</title>
        
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700&family=MedievalSharp&display=swap" rel="stylesheet">
        
        <style>
            /* Reset e Estilos Globais */
            * {
                box-sizing: border-box;
                margin: 0;
                padding: 0;
            }

            body {
                background-color: #0f0c08; /* Tom escuro medieval */
                color: #e6d5b8;            /* Cor de pergaminho antigo */
                font-family: 'MedievalSharp', cursive, serif;
            }

            /* Container Principal */
            main {
                display: flex;
                align-items: center;
                justify-content: space-between;
                margin: 8% 10%;
                gap: 40px;
            }

            /* Conteúdo do Texto */
            .apresentacao__conteudo {
                width: 615px;
            }

            h1 {
                font-family: 'Cinzel', serif;
                font-size: 36px;
                line-height: 1.3;
                margin-bottom: 20px;
            }

            .texto-destaque {
                color: #d4af37; /* Dourado místico */
            }

            p {
                font-size: 20px;
                line-height: 1.6;
                margin-bottom: 30px;
                color: #c0b096;
            }

            /* Seção dos Links / Botões */
            .apresentacao__links {
                display: flex;
                flex-direction: column;
                align-items: flex-start;
                gap: 16px;
            }

            .apresentacao__links__subtitulo {
                font-family: 'Cinzel', serif;
                font-size: 22px;
                font-weight: 700;
                color: #d4af37;
            }

            /* Estilo das Guildas / Botões */
            .apresentacao__links__link {
                display: flex;
                justify-content: center;
                align-items: center;
                gap: 16px;
                border: 2px solid #d4af37;
                width: 380px;
                padding: 14px 0;
                border-radius: 6px;
                background-color: #1a140e;
                color: #e6d5b8;
                text-decoration: none;
                font-family: 'Cinzel', serif;
                font-size: 18px;
                font-weight: 700;
                transition: 0.3s;
            }

            /* Efeito ao passar o mouse */
            .apresentacao__links__link:hover {
                background-color: #d4af37;
                color: #0f0c08;
                box-shadow: 0 0 15px rgba(212, 175, 55, 0.5);
            }

            /* Imagem do Perfil / Personagem */
            .imagem-personagem {
                width: 400px;
                border: 4px solid #d4af37;
                border-radius: 12px;
                box-shadow: 0 0 20px rgba(212, 175, 55, 0.2);
            }
        </style>
    </head>
    <body>
        <main>
            <section class="apresentacao__conteudo">
                <h1>Bem-vindo à minha Guilda de Arte! Abra o livro e <strong class="texto-destaque">descubra minhas criações!</strong></h1>
                
                <p>Olá aventureiro, meu nome é Arthur. Toda grande aventura começa com uma pequena ideia.
A minha começou com um lápis, muita imaginação e vontade de criar.
Hoje, exploro o universo do desenho, do design e da arte digital.
Cada projeto é uma nova experiência e uma nova habilidade conquistada.
Quem sabe até onde essa aventura pode chegar?</p>
                
                <div class="apresentacao__links">
                    <h2 class="apresentacao__links__subtitulo">Acesse minhas Guildas:</h2>
                    
                    <a class="apresentacao__links__link" href="https://scratch.mit.edu/projects/1096654082/editor" target="_blank">
                        🛡️ Forja da Programação
                    </a>
                    
                    <a class="apresentacao__links__link" href="https://www.instagram.com/arthur.fariash/" target="_blank">
                        🔮 Taverna do Instagram
                    </a>
                </div>
            </section>
            
            <img class="imagem-personagem" src="download (5).png" alt="Avatar do Arthur">
        </main>
    </body>
</html>
