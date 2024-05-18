<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Calculator</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div id="calculator">
      <input id="display" readonly />
      <div id="keys">
        <button onclick="appendToDisplay('+')" class="beda-dari">+</button>
        <button onclick="appendToDisplay('-')" class="beda-dari">-</button>
        <button onclick="appendToDisplay('x')" class="beda-dari">x</button>
        <button onclick="appendToDisplay(':')" class="beda-dari">:</button>
        <button onclick="appendToDisplay('7')">7</button>
        <button onclick="appendToDisplay('8')">8</button>
        <button onclick="appendToDisplay('9')">9</button>
        <button onclick="appendToDisplay('4')">4</button>
        <button onclick="appendToDisplay('5')">5</button>
        <button onclick="appendToDisplay('6')">6</button>
        <button onclick="appendToDisplay('1')">1</button>
        <button onclick="appendToDisplay('2')">2</button>
        <button onclick="appendToDisplay('3')">3</button>
        <button onclick="appendToDisplay('.')">.</button>
        <button onclick="clearDisplay()" class="operator-btn">AC</button>
        <button onclick="calculate()" class="samadengan">=</button>
      </div>
    </div>
    <script src="index.js"></script>
  </body>
</html>
