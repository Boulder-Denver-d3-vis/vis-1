##  Enter

Given a data binding

    d3.select("body").selectAll("div").data([0,1,2])

Tell D3 what to do when there is no corresponding document element for a data element:

    <body></body>

<br/>

    d3.select("body").selectAll("div").data([0,1,2]).enter().append("div");

"Inside the body tag, bind each element of [0,1,2] to a div, creating it inside body if it doesn't exist."
