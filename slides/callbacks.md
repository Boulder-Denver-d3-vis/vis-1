## Callbacks

***

When setting attributes or styles on bound elements, you can supply a callback.

    myData = [{ size: 10}, {size: 2}];
    ...
    mySelection.attr("r", function(d,i) { return d.size; });

The bound data and its index in the data array get passed in.

The return value is gets set as the attribute value.

