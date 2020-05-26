# What should I do?
Bored?
Can't think of anything to do?
**Run** this generator for an idea!

<html>

<button onclick="myTask(./whattodo.txt)">let's go</button>

<script>
  
function myTask(file) {

 var rawFile = new XMLHttpRequest();
    rawFile.open("GET", file, false);
    rawFile.onreadystatechange = function ()
    {
        if(rawFile.readyState === 4)
        {
            if(rawFile.status === 200 || rawFile.status == 0)
            {
                var allText = rawFile.responseText;
                alert(allText);
            }
        }
    }
    rawFile.send(null);
alert("this is working");
}
</script>
    
</html>
  
