# Original Version
Bored? edited
Can't think of anything to do? 
**Run** this generator for an idea!

<code>

<html>
  
<button onclick="myTask()">let's go</button>

<script>
	const url = "https://raw.githubusercontent.com/Hope-T/whattodo/gh-pages/whattodo.txt";

let myTask = async () => {
	let response = await fetch(url)
	if (response.status == 200)
		alert(await response.text())
}


</script>
</html>
  
</code>

