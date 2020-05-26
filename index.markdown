# What should I do?
Bored?
Can't think of anything to do?
**Run** this generator for an idea! 
  <html>
      <button onclick="findTask()">let's go</button>
       <script>
    
           function findTask(){
            var fs = require("fs");
            var text = fs.readFileSync("./whattodo.txt").toString('utf-8');
            var textByLine = text.split("\n");
            alert(textByLine[0]);
            alert("This is working");
           }
    
  </script>
  </html>
  
