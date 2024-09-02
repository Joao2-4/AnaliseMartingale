<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

<h1>Martingale Bot de Aposta</h1>

<p>
        Este repositório contém um bot desenvolvido em Python com auxílio de Selenium para aplicar o método de
        Martingale em casas de aposta online.
</p>

<h2>Sobre o Método de Martingale</h2>
    <p>
        O método de Martingale é uma técnica popular, especialmente em jogos de azar, como a roleta, onde as apostas
        são feitas em eventos com duas possíveis saídas, como vermelho ou preto.
    </p>

<h3>Como Funciona</h3>
    <p>
        A ideia básica do método de Martingale é simples: após cada perda, você dobra o valor da sua aposta na rodada
        seguinte. Quando eventualmente você ganhar, o lucro obtido será suficiente para cobrir todas as perdas
        anteriores, mais um pequeno ganho equivalente à aposta original.
    </p>

<h4>Exemplo:</h4>
    <ul>
        <li><strong>Aposta Inicial:</strong> Você começa apostando 1 unidade.</li>
        <li><strong>Se Perder:</strong> Você aposta 2 unidades na próxima rodada.</li>
        <li><strong>Se Perder Novamente:</strong> Você aposta 4 unidades.</li>
        <li><strong>Se Perder Mais Uma Vez:</strong> Você aposta 8 unidades.</li>
        <li><strong>Se Ganhar:</strong> Você recupera todas as apostas anteriores e obtém um lucro de 1 unidade.</li>
    </ul>

<h2>Implementação</h2>
    <p>
        A implementação deste bot foi feita utilizando <a href="https://www.python.org/">Python</a> e a biblioteca
        <a href="https://www.selenium.dev/">Selenium</a>. O bot automatiza o processo de apostas em uma casa de apostas
        online, aplicando a estratégia de Martingale para maximizar as chances de lucro.
    </p>

<h2>Motivação</h2>
    <p>
        A ideia de criar o bot surgiu após a criação de um artigo sobre o método de Martingale aplicado ao mercado
        financeiro, com uso de bolsa de valores.
    </p>

<h2>Como Usar</h2>
    <ol>
        <li>Clone este repositório.</li>
        <li>Instale as dependências necessárias:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Configure os parâmetros do bot no arquivo <code>config.py</code>.</li>
        <li>Execute o bot:</li>
        <pre><code>python martingale_bot.py</code></pre>
    </ol>

<h2>Atenção</h2>
    <p>
        O uso deste bot é de total responsabilidade do usuário. Apostar online envolve riscos, e não há garantia de
        lucro. O método de Martingale, apesar de ser uma estratégia conhecida, pode resultar em perdas significativas,
        especialmente se a sequência de perdas for longa.
    </p>

<h2>Licença</h2>
    <p>
        Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo <code>LICENSE</code> para mais
        detalhes.
    </p>

</body>

</html>
