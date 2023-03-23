
<span class="tooltip">Hover over me
  <span class="tooltiptext">
    | Key   | Value    |
    |-------|----------|
    | A     | Alpha    |
    | B     | Bravo    |
    | C     | Charlie  |
    | D     | Delta    |
  </span>
</span>
.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 1px dotted black;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: #555;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}

## Code Snippets


#### On Paint
```
game.onPaint(function() {

})
```
#### Print Center
```
Image.printCenter(String, y, color,)
```
1. Replace `Image` with your image (usually `screen`)
2. Replace `String` with your text
3. Replace `y` with the y
4. Replace `Color` with your color 
#### Print Text
```
Image.print(String, x, y, color,)
```
1. Replace `Image` with your image (usually `screen`)
2. Replace `String` with your text
3. Replace `x` with the x
3. Replace `y` with the y
4. Replace `Color` with your color 
## Declaring
### Formats
- Number = `type:Number`
- Text = `type:String`
- Boolean = `type:Boolean`
- Any = `type:Any`
- Image = `type:Img` or `type:Image`
- Any = `type:Any`
- A = `type:Any`
### Arrays



