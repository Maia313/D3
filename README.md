# D3

### Methods

+ `select()`;
+ `append()`;
+ `text()`;
+ `selectAll()`;
+ `selection.text((d) => d)`;

```js
d3.select("ul").selectAll("li")
.data(dataset)
.enter()
.append("li")
.text("New item")
.style("color", d => d >= 20 ? "red" : "blue")
.attr("class", "container");
```


