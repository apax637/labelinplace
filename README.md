LabelinPlace
============

A simple fully customizable form enhancement plugin for in-field label support.  

Visit the [project page](http://andreapace.co.uk/labelinplace/) for more information and usage examples!

Install
============
Four simple steps to install and configure labelinplace plugin
### Step 1. Include jQuery

Include the last version of jQuery
```bash
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
```

### Step 2. Include jQuery Words Rotator Code

Insert into your page's head tag:
```bash
<link rel="stylesheet" href="jquery.labelinplace.css">
<script src="jquery.labelinplace.js"></script>
```
### Step 3. HTML code
```bash
<label for="name">Your name</label>
<input type="text" class="labelinplace" name="name">
```
### Step 5. Javascript code
```bash
<script type="text/javascript">
    $(function () {
        $(".labelinplace").labelinplace();
    });
</script>

```
Configure
============
```bash
$("#myForm .mylabel").labelinplace({
    labelPosition: "up",                   //position for the placeholder [up|down]
    classPlaceholder: "mypaceholder",       //class for the label when act as placeholder
    classLabel: "mylabel",                  //class for the label when act as label
    classIcon: "myicon",                    //class for the icon container
    wrapperClass: "mygroup",                //class for wrapper of the input+label
    animSpeed: 200,                         //speed of the animation
    labelArrowDown: null,                   //down icon (image or font) 
    labelArrowUp: null,                     //up icon (image or font)
    labelArrowRight: null,                  //right icon (image or font)
    labelIconPosition: "append"             //position of the icon [append|propend]
    inputAttr: "name"                       //the attribute that contains the name of INPUT/TEXTAREA
});
```
License
============
Labelinplace is licensed under the [MIT license](http://opensource.org/licenses/MIT).
