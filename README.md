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
To stack things on top of each other.

```
Stack(
              children: <Widget>[
                SizedBox(
                  width: 300,
                  height: 300,
                  child: Container(color: Colors.green),
                ),
                SizedBox(
                  width: 200,
                  height: 200,
                  child: Container(color: Colors.yellow),
                ),
                SizedBox(
                  width: 100,
                  height: 100,
                  child: Container(color: Colors.red),
                )
              ],
            ))
```
The stack has `alignment` option with nine possible values. `centerLeft`,`topLeft`,`topCenter` etc.

**Positioned Widget** 



### Debugging / Logging / Breakpoints (https://www.youtube.com/watch?v=P9P6o7OLS00)

##### Print Function
* print("String here")
* `dev.log("message", name: '__selvesan', error: {"data": "Error of data"});`
* `dev.debugger();` to add break points.



### Height and Width of screen.
```
    Size size = MediaQuery.of(context).size;
    print(size.height);
    print(size.width);

```

