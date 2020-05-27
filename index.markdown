# What should I do?
Bored?
Can't think of anything to do? yy
**Run** this generator for an idea!

<html>

<script id="listOfTasks" data-search="text" src="file:///users/hopetsai/Downloads/whattodo.txt" >
var script_tag = document.getElementById('listOfTasks')
var search_term = script_tag.getAttribute("data-search");
  
<button onclick="myTask(search_term)">let's go</button>

<script>
  
function myTask(file) {
var text = file.toString();
text = text.split("\n");
alert(text[0]);
}
</script>
    
</html>
  
