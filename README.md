# fltr_doc

### Row & Column

* Align Content Vertically `Column`
* Align Content Horizontally `Row`

Both `Row` and `Column` have three other controls 

* **mainAxisAlignment** (The children of the Row or Column can align their position according to the size of Row or Column. Has controls `start`,`end`,`center`,`space between`,`space around`,`space evenly` of the row)

* **mainAxisSize** (How much space our rows or columns take within it's container. Has two possible values `min` or `max`)

* **crossAxisAlignment**  (Refers to the axis with reference to the mainAxis. Has controls `start`,`end`,`center`,`stretch`(strech is used to extend all the available space of it's parent))


### Baseline
The baseline is a special crossAxisAlignment option that is useful when rendering text. If we have multiple text widget in a row and they are all different sizes this option gives you a way of aligning to their common baseline i.e all the text equally align at the same place at their bottom.


### Stack
