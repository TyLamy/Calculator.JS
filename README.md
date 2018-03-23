# Calculator.JS

<form name = "calc" id = "calc">  
     <input type = "text"  id = "solutionBox" style = "text-align:center;background:blue;" disabled = "disabled">  
    </form>  
      
    <table>  
 
     <tr>  
      <td><input type = "button" value = "7" onclick = "calc.solutionBox.value += '7'"></td>  
      <td><input type = "button" value = "8" onclick = "calc.solutionBox.value += '8'"></td>  
      <td><input type = "button" value = "9" onclick = "calc.solutionBox.value += '9'"></td>  
      <td rowspan = "2"><input type = "button" onclick = "calc.solutionBox.value += '+'" style = "height: 60px;" value = "+"></td>  
     </tr>  
     <tr>  
      <td><input type = "button" value = "4" onclick = "calc.solutionBox.value += '4'"></td>  
      <td><input type = "button" value = "5" onclick = "calc.solutionBox.value += '5'"></td>  
      <td><input type = "button" value = "6" onclick = "calc.solutionBox.value += '6'"></td>  
     </tr>  
     <tr>  
      <td><input type = "button" value = "1" onclick = "calc.solutionBox.value += '1'"></td>  
      <td><input type = "button" value = "2" onclick = "calc.solutionBox.value += '2'"></td>  
      <td><input type = "button" value = "3" onclick = "calc.solutionBox.value += '3'"></td>  
      <td rowspan="3">
      <input type = "button" onclick = "calc.solutionBox.value = eval(calc.solutionBox.value)" style="height: 80px;" value ="="></td>  
     </tr>  
     <tr>  
      <td><input type = "button" value = "0"  onclick = "calc.solutionBox.value += '0'"></td>  
      <td><input type = "button" value = "."  style="width: 100%" onclick = "calc.solutionBox.value += '.' "></td>  
      <td><input type = "button" value = "-"  onclick = "calc.solutionBox.value += '-'" ></td> 
     </tr>  
         <tr>  
      <td><input type = "button" value = "C"   onclick = "calc.solutionBox.value = ''"></td>  
      <td><input type = "button" value = "/"   onclick = "calc.solutionBox.value += '/'"></td>  
      <td><input type = "button" value = "x"   onclick = "calc.solutionBox.value += 'x'"></td>  
 
     </tr>  
    </table>  
