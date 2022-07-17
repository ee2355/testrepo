DOCTYPE html>
    <head>
    <script src="script.js"></script>
    <link rel="stylesheet" href="style.css">
    <title>Simple Interest Calculator</title>
    </head>
    <div class=maindiv>
        <h1>Simple Interest Calculator</h1>

        Amount <input type="number"  id="principal">  <br/>
        Rate <input type="range" id="rate" min="1" max="20" step="0.25" value="10.25"><span id="rate_val">
            10.25%
            </span> <br>
        
        No. of Years <select id="years">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
        </select> <br/>
        Interest : 10.25% <span id="result"></span><br>

        <button onclick="compute()">Compute interest</button>
        <span id="result"></span> <br>

        <footer>

            &#169; This Calculator belongs to EE
    
    
    </footer>
    </div>
</html>
![image](https://user-images.githubusercontent.com/109462333/179394581-01af72b9-2d75-4f77-81f5-e5f5280d95fb.png)
