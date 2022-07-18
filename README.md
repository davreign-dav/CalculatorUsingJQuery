# CalculatorUsingJQuery


<html lang="en">

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <title>CALCULATOR</title>
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
            integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
            crossorigin="anonymous"></script>

        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
            integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">

    </head>

    <body>
        <div class="container">
            <div class="outer-frame">
                <div class="display-result">
                    <div class="input" id="input"></div>
                </div>
                <div class="flex-row">
                    <button class="value">7</button>
                    <button class="value">8</button>
                    <button class="value">9</button>
                    <button class="value">*</button>
                </div>

                <div class="flex-row">
                    <button class="value">4</button>
                    <button class="value">5</button>
                    <button class="value">6</button>
                    <button class="value">-</button>
                </div>

                <div class="flex-row">
                    <button class="value">1</button>
                    <button class="value">2</button>
                    <button class="value">3</button>
                    <button class="value">+</button>
                </div>
                <div class="flex-row">
                    <button class="value">0</button>
                    <button class="value">.</button>
                    <button class="value">/</button>
                    <button class="value" id="clear">C</button>
                </div>
                <div class="flex-row">
                    <button class="value enter" id="result">Enter</button>
                </div>

            </div>

        </div>
        <script src="https://code.jquery.com/jquery-3.6.0.js"
            integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>

        <script src="script.js"></script>
    </body>

</html>
