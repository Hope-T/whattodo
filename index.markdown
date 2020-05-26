# What should I do?
Bored?
Can't think of anything to do?
**Run** this generator for an idea!

<html>

<button onclick="myTask()">let's go</button>

<script>
  
function myTask() {
const fs = require('fs') 
  
fs.readFile('whattodo.txt', (err, data) => { 
    if (err) throw err; 
  
    alert(data.toString()+""); 
}) 
}
</script>
    
</html>
  
