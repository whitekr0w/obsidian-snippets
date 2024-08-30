<%* 
if (tp.file.title == "Untitled") { 
    var title = await tp.system.prompt("Provide name for file: ", "")
} else { 
    var title = tp.file.title 
} 
await tp.file.rename(title) 
await app.commands.executeCommandById('templater-obsidian:insert-templater') 
%>