<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .calculator {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 25px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            max-width: 350px;
            width: 100%;
        }
        
        .display {
            background: rgba(0,0,0,0.2);
            color: white;
            font-size: 2.5em;
            padding: 20px;
            border-radius: 15px;
            text-align: right;
            margin-bottom: 20px;
            min-height: 80px;
            display: flex;
            align-items: center;
            justify-content: flex-end;
            word-break: break-all;
        }
        
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }
        
        button {
            height: 70px;
            border: none;
            border-radius: 15px;
            font-size: 1.5em;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.2s;
            backdrop-filter: blur(5px);
        }
        
        .number {
            background: rgba(255,255,255,0.2);
            color: white;
        }
        
        .number:hover {
            background: rgba(255,255,255,0.3);
            transform: scale(1.05);
        }
        
        .operator {
            background: rgba(255,193,7,0.8);
            color: white;
        }
        
        .operator:hover {
            background: rgba(255,193,7,1);
        }
        
        .equals {
            background: rgba(76,175,80,0.8);
            color: white;
            grid-column: span 2;
        }
        
        .equals:hover {
            background: rgba(76,175,80,1);
        }
        
        .clear {
            background: rgba(244,67,54,0.8);
            color: white;
        }
        
        .clear:hover {
            background: rgba(244,67,54,1);
        }
        
        @media (max-width: 400px) {
            .calculator {
                padding: 20px;
            }
            button {
                height: 60px;
                font-size: 1.3em;
            }
        }
    </style>
</head>
<body>
    <div class="calculator">
        <div class="display" id="display">0</div>
        <div class="buttons">
            <button class="clear" onclick="clearAll()">C</button>
            <button class="deleteLast" onclick="deleteLast()">⌫</button>
            <button class="operator" onclick="appendToDisplay('/')">/</button>
            <button class="operator" onclick="appendToDisplay('*')">*</button>
            <button class="number" onclick="appendToDisplay('7')">7</button>
            <button class="number" onclick="appendToDisplay('8')">8</button>
            <button class="number" onclick="appendToDisplay('9')">9</button>
                <button class="operator" onclick="appendToDisplay('-')">-</button>
                <button class="number" onclick="appendToDisplay('4')">4</button>
                <button class="number" onclick="appendToDisplay('5')">5</button>
                <button class="number" onclick="appendToDisplay('6')">6</button>
                <button class="operator" onclick="appendToDisplay('+')">+</button>
                <button class="number" onclick="appendToDisplay('1')">1</button>
                <button class="number" onclick="appendToDisplay('2')">2</button>
                <button class="number" onclick="appendToDisplay('3')">3</button>
                <button class="equals" onclick="calculateResult()" rowspan="2">=</button>
                <button class="number" onclick="appendToDisplay('0')">0</button>
                <button class="decimal" onclick="appendToDisplay('.')">.</button>
        </div>
    </div>
    <script>
        let display=document.getElementById('display');
        let currentInput='0';
        let shouldResetDisplay=false;

        function appendToDisplay(value){
            if(shouldResetDisplay){
                currentInput='';
                shouldResetDisplay=false;
            }
            if(currentInput==='0' && value !=='.'){
                currentInput=value;
            }else{
                currentInput+=value;
            }
            display.textContent=currentInput;
        }
        function clearAll(){
            currentInput='0';
            display.textContent=currentInput;
            shouldResetDisplay = false;
        }
        function deleteLast(){
            if(currentInput.length>1){
                currentInput=currentInput.slice(0,-1);
            }else{
                currentInput='0';
            }
            display.textContent=currentInput;
        }
        function calculateResult(){
            try{
                let expression=currentInput.replace(/×/g, '*');
                let result=eval(expression);
                if(!isFinite(result)){
                    throw new Error("Math Error");
                }  
                currentInput=result.toString();
                display.textContent=currentInput;
                shouldResetDisplay=true;
            }catch(error){
                display.textContent="Error";
                currentInput='0';
                shouldResetDisplay=true;
            }
            document.addEventListener('keydown',function(event){
                const key = event.key;
            if (key >= '0' && key <= '9' || key === '.') {
                appendToDisplay(key);
            } else if (key === '+' || key === '-') {
                appendToDisplay(key);
            } else if (key === '*') {
                appendToDisplay('*');
            } else if (key === '/') {
                appendToDisplay('/');
            } else if (key === 'Enter' || key === '=') {
                calculate();
            } else if (key === 'Escape' || key === 'c' || key === 'C') {
                clearAll();
            } else if (key === 'Backspace') {
                deleteLast();
            }
            });
        }
    </script>
</body>
</html>
