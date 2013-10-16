##  Exit

Given an existing data binding, with elements created via `enter()`

    d3.select("body").selectAll("div").data([0,1,2]).enter().append("div");

Tell D3 what to do when there's no data to be bound to an element:

    d3.select("body").selectAll("div").data([]).exit().remove();

"If there's no data for an existing element, `remove()` it."
