# My Markdown Page

This is some sample text with a mini menu. Hover over the text below to see the menu:

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

Here is some more sample text.

## Subheading

Here is some additional text.

### Sub-Subheading

Here is even more text.

<style>
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
</style>
