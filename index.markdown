# What should I do?
Bored?
Can't think of anything to do? yy
**Run** this generator for an idea!

<html>
  
<button onclick="myTask()">let's go</button>

<script>
  
function myTask() {

 var rawFile = new XMLHttpRequest();
    rawFile.open("GET", 'whattodo.txt', false);
    rawFile.onreadystatechange = function ()
    {
        if(rawFile.readyState === 4)
        {
            if(rawFile.status === 200 || rawFile.status == 0)
            {
                var allText = rawFile.responseText;
                var text = allText.split("\n");
                alert(text[0] + "is there an alert"?);
            }
        }
    }
    rawFile.send(null);
//var text = file.toString();
//text = text.split("\n");
//alert(text[0]);
}
</script>
    
</html>
  
