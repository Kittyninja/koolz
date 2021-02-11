# KOOLS

A few tools to add CSS, find values, name generation, button assigning, and other things. 
To add KOOLS to your website, add this to your index.html file:

```
<script src = "https://cdn.jsdelivr.net/gh/Kittyninja/tools/lib.js"></script>
```

# Documentation


1. _pushTo
```
_pushTo(your array, the index for your item, item)

_pushTo(myArray,3,"hello world")
```
To push an item to a specific part of an array, use _pushTo().

2. _makeColor
```
_makeColor(target id, rgb1, rgb2, rgb3)

_makeColor("myId",255,0,0)
```

To change the text color of an HTML element, use _makeColor() to set it.

3. _findAll
```
_findAll(value)

_findAll("myClass")
```

To find all elements with classes that match your entered value, use _findAll().

4. _makeName

```
_makeName(includes last name, male/female)

console.log(_makeName(true,male))
```
