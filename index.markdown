# Original Version
Bored?
Can't think of anything to do? 
**Run** this generator for an idea!

# Fixed Version
<code>
<button onclick="myTask()">let's go</button>
  
const url = "https://raw.githubusercontent.com/Hope-T/whattodo/gh-pages/whattodo.txt";
let myTask = async () => {
	let response = await fetch(url)
	if (response.status == 200)
		alert(await response.text())
}

</code>
