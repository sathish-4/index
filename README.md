<!doctype html>
<html>
    <head>
<title>Web app</title>
    
    <link rel="stylesheet" href="style.css">
    <script src="scrpt.js"></script><br>
    </head>

    <body>
     <div class="maindiv">
        
        <h1>Simple Interest Calculator</h1>
       
                Amount <input type="text"  id="principal">  <br><br>
       Interest rate <input type="range" min="1" max="20" step="0.25" value="10.25" id="rate" name="rate" onchange="SliderValue()"> 
                                <span id="rate_display">10%</span><br><br>
        No of years :<select name="years" id="years">
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
                                </select><br><br>


         <button id="compute" onclick="compute()">Compute Interest</button> <br><br>
                <span id="result">
        


    Interest : <span id="result"></span><br>

  
    <footer>

                &#169; Everyone Can Get Rich <br/>
                This Calculator belongs to Sathish kumar
        
        
        </footer> <br/> 
    

   </div>
     
    </body> 
</html>


