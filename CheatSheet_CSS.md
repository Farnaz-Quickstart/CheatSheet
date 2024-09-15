# Bootstrap Cheetsheat

## Margin, Padding

**<span style="color:green">{property}{sides}-{size}</span>**<br>
{property} is either
- m: for classes that set margin
- p: for classes that set padding<br>

{sides} is either 
- t: for classes that set margin-top or padding-top
- b: for classes that set margin-bottom or padding-bottom
- s: (start) for classes that set margin-left or padding-left in LTR, margin-right or padding-right in RTL
- e: (end) for classes that set margin-right or padding-right in LTR, margin-left or padding-left in RTL
- x: for classes that set both *-left and *-right
- y: for classes that set both *-top and *-bottom
blank - for classes that set a margin or padding on all 4 sides of the element
- {sides} specifies which side(s) the spacing applies to:

{size} is either <br>
- 0: for classes that eliminate the margin or padding by setting it to 0
- 1: for classes that set the margin or padding to $spacer * .25
- 2: for classes that set the margin or padding to $spacer * .5
- 3: for classes that set the margin or padding to $spacer
- 4: for classes that set the margin or padding to $spacer * 1.5
- 5: for classes that set the margin or padding to $spacer * 3
- auto - for classes that set the margin to auto<br>
The spacing scale for margin (m) and padding (p) classes is based on a rem unit (relative to the root font size). By default, 1 rem equals 16 pixels.
