# What should I do?
Bored?
Can't think of anything to do?
**Run** this generator for an idea! 
  <html>
  <script>
    var fs = require("fs");
    var text = fs.readFileSync("./whattodo.txt").toString('utf-8');
    var textByLine = text.split("\n");
    alert(textByLine[0]);
    
  </script>
  <button type="button" name="generate" class="btn">let's go</button>
  </html>
  
