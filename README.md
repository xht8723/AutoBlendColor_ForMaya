# AutoBlendColor_ForMaya
A script to set up IK FK switch via BlendColors in Maya

# Installation
Copy all files into your Maya's script folder

e.g:C:\Users\XXXX\Documents\maya\2022\scripts

Add a button on Maya shelf that excute the following scripts:

```python
from AutoBlendColor import blendColor
import imp
imp.reload(blendColor)
