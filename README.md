# Text  from/to .XML
blender addon to export/import text objects as .XML file

the addon is useful when  you need to edit a lot of text objects externaly , you can export them to .xml file and edit them then synchronize them with the import function (no other properties will be changed only the body "content" of the text object is updated )

 - all text objects from all scenes are exported 
 - the .xml fil will have the following structure :

 
```XML

<?xml version="1.0" ?>
<data>
	<scene name="Scene">
		<object name="Text.002">Text</object>
		<object name="Text.001">Text</object>
		<object name="Text">Text</object>
	</scene>
	<scene name="Scene.001">
		<object name="Text.005">Text</object>
		<object name="Text.004">Text</object>
		<object name="Text.003">Text</object>
	</scene>
</data>

```

### Using the addon :

 - hit <kbd>Space</kbd> and type "text from" and select "text from-to xml"

 OR
 
 - go to File-->Import/Export-->text from-to xml
 
 - choose wether to export or import from the tools panel :

![image](http://i.stack.imgur.com/bAh3W.png)
