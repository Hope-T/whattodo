# Original Version
Bored? edited
Can't think of anything to do? 
**Run** this generator for an idea!

<code>

<html>
  
<button onclick="myTask()">let's go</button>

<script>
 var file = "whattodo.txt";
  
function myTask() {
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
}

}
</script>
</html>
  
</code>

# Fixed Version

<code>
  
const url = "https://raw.githubusercontent.com/Hope-T/whattodo/gh-pages/whattodo.txt";
let myTask = async () => {
	let response = await fetch(url)
	if (response.status == 200)
		alert(await response.text())
}

</code>
