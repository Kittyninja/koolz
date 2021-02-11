# KOOLZ

A few tools to add CSS, find values, name generation, button assigning, and other things. 
To add KOOLZ to your website, add this to your index.html file:

```
// version 1
<script src = "https://cdn.jsdelivr.net/Kittyninja/koolz/main/koolz.1.1.js"></script>

// version 2
<script src = "https://cdn.jsdelivr.net/Kittyninja/koolz/main/koolz.1.2.js"></script>
```

Or download it and use this refrence:
```
<script src = "/koolz-main/koolz.1.1.js"></script>
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

console.log(_makeName(true,"male"))
```
Returns a random name.

5. _id

```
_id(id)

const p = _id(p)
```
Quickly finds an ID.

6. _findIt()

```
_findIt(thing,array)

console.log(_findIt("pagono",myArray))
```
Finds something from an array and returns the value (works on objects as well).

# Canvas Tools

To access a canvas (**MUST BE FIRST**) use _accessCanvas(yourCanvasId).
Then use the following tools.

```
rec(x,y,w,h)
```
Draws a rectangle at x, y, w width, and h height.

```
line(startx,starty,endx,endy)
```
Draws a line at startx and starty to endx and endy.

```
paint(rgb1,rgb2,rgb3)
```
Sets the fill to your given color.

```
oval(x,y,width,height)
```
Makes an oval (or circle if width and height are the same) at x and y with w width and h height.



