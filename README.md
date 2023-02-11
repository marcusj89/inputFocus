# inputFocus

inputFocusOther - separate version




How an svg behaves depends on how is it's being implemented


#### object - standalone file

```
<embd src="">       like a png or animated gif but still a self contained object and if we want
<object data="">     to change anything still have to go to the original file
<iframe src="">
```

#### image css
  
```  
 <img src="">
 background: url('...')
```  

```
<svg></svg>  
```


#### about svg

```
view box= "0 0 20 20"
```

it defines a space that has an aspect ratio of 1 to 1 or a square.
it sets the relatively size of pixels within the svg.


```
(0,0)
----- w -----
|           |
|           |
|           |
------------- (20,20)

```


#### inline

- vector image format capable to interact with js
- inline svgs gives u the most flexibility.  svg markup written in an html document
- removes the  separation from the svg and the rest of the app.. like an extra set of html tags
for drawing
- it can be control with css and javascript best for user interaction


  
