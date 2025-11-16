# resourcepack-template
A simple template for texture packs with custom modeldata.

### **there are a few steps to do before you can actualy start customizing.**

1. change the namespace
2. add a json file for your item and model
3. add your texture

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
