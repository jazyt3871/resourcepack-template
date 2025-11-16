# resourcepack-template
A simple template for texture packs with custom modeldata.

### **there are a few steps to do before you can actualy start customizing.**

1. change the namespace
2. add a json file for your item
3. also add a json for the models/item folder
4. add your texture

**Step 1**
- inside of "template\assets\" rename the folder called "your-namespace-here" to whatever you want it to be.
- make sure you dont call it "minecraft"
**Step 2**
- goto "template\assets\your-namespace-here"
- there is 3 folders, first start by going inside of "items" and make a copy of the "template.json"
- and replace "your-namespace-here" with what you chose
- also replace "template" with the name of your item
```
{
    "model": {
        "type": "minecraft:model",
        "model": "your-namespace-here:item/template"
    }
}
``` 
- for example 
```
{
    "model": {
        "type": "minecraft:model",
        "model": "jaz:item/subscribe"
    }
}
```
**Step 3**
- make a copy of the "template.json" inside of "template\assets\your-namespace-here\models\item"
- rename the copy to your item and open it
- edit the json code, change the "your-namespace-here" to your namespace and "template" to your item's texture's name
```
{
    "parent": "minecraft:item/generated",
    "textures": {
        "layer0": "your-namespace-here:item/template"
    }
}
```
- for example
```
{
    "parent": "minecraft:item/generated",
    "textures": {
        "layer0": "jaz:item/subscribe"
    }
}
```
**Step 4**
- add your texture to "template\assets\your-namespace-here\textures\item"
- make sure its a ".png" file

if something isnt working out for you, i also made a tutorial at "!!youtube link here!!"
or just add me on discord "nr1_jaz"
