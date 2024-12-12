ATIVIDADE DO CURSO DE PROGRAMAÇÃO E DESENVOLVIMENTO WEB FULLSTACK - ESCOLA PIXELS E IW TRAINING.

Atividade de HTML e CSS para fazer um site com resolução para mobile, tablet, netbook e pc.

O professor entregou o HTML e CSS feitos até aqui:

HTML: 
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Lanchonete Ideal</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <section id="produtos">
            <!-- início do produto -->
            <article class="produto pizza">
                <h2 class="titulo">
                    PIZZA
                </h2>
            </article>
            <!-- fim do produto -->

            <!-- início do produto -->
            <article class="produto promocao">
                <h2 class="titulo">
                    PROMOÇÕES
                </h2>
            </article>
            <!-- fim do produto -->

            <!-- início do produto -->
            <article class="produto esfiha">
                <h2 class="titulo">
                    ESFIHAS
                </h2>
            </article>
            <!-- fim do produto -->

            <!-- início do produto -->
            <article class="produto fogazza">
                <h2 class="titulo">
                    FOGAZZAS
                </h2>
            </article>
            <!-- fim do produto -->

            <!-- início do produto -->
            <article class="produto beirute">
                <h2 class="titulo">
                    BEIRUTES
                </h2>
            </article>
            <!-- fim do produto -->

            <!-- início do produto -->
            <article class="produto pastel">
                <h2 class="titulo">
                    PASTÉIS
                </h2>
            </article>
            <!-- fim do produto -->
        </section>
    </body>
</html>

e o CSS até aqui:
body {
    background: #fff;
    }

#produtos {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 5px;
    }

    

        .pizza {
            background: url('produtos/pizza.png');
            }

        .promocao {
            background: url('produtos/oferta-do-dia.png');
            }

        .esfiha {
            background: url('produtos/esfihas.png');
            }

        .fogazza {
            background: url('produtos/fogazza.png');
            }

        .beirute {
            background: url('produtos/beirute.png');
            }

        .pastel {
            background: url('produtos/pastel.png');
            }

    .produto {
        height: 170px;
        border-radius: 10px;
        background-size: cover;
        transition: all 0.3s ease;
        
        }

        .titulo {
            margin-top: 141px;
            padding: 5px 10px;
            background: #000;
            color: #fff;
            font-size: 16px;
            font-family: Trebuchet MS;
            opacity: 0.85;
            border-radius: 0px 0px 10px 10px;
            }

    .produto:hover {
        opacity: 0.9;
        transform: scale(0.9);
        transition: all 0.3s ease;
        cursor: pointer;
        }

O restante do projeto foi todo feito e desenvolvido por mim com ajuda de IA.
