## Labeling Policy (instruction included)
### 1.0 Vegetation
- 1. enter photo shop，press alt+F9 to open Action menu，load action script "ps-annotation.atn"
![selection](../img/action.png)
- 2. open the src url, and press CTRL+F2，a raw mask of vegetation would be generated
![selection](../img/selection.png)

- 3. adjust the selected area by hand(lasso is recommended, just press shift/alt and drag the mouse)
- 4. then press CTRL+F3 to generate bitmap, save it by "_t.png" suffix，"DJI_0285_t.png",e.g.

*Annotation example*
![vegetation](../img/DJI_0285_t.png)

**[Chinese version of annotation instruction](ps-annotation.pdf)**

### 1.1 Building
- 1. new a black layer, using polygon lasso to select building and fill it with black
- 2. press CTRL+F3 to generate bitmap, save it by "_b.png" suffix，"DJI_0285_b.png",e.g.

*example of annotated result*
![Building](../img/DJI_0285_b.png)

### 1.2 Other classes
- 1. After filled ROI with black, press CTRL+F3 to generate bitmap. Remember to save it by suffix(see **Class Definitions** above)