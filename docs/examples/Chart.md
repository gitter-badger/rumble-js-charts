In this example we use [<Chart />](#Chart) to defined size and data for your chart. It wraps [<Bars />](#Bars) component 
that draws bar chart. 

You can change `<Bars />` to `<Lines />`, `<Dots />` or `<Pies />`. 
Also you can put all these 4 components all together in different order.

```
// EVERY EXAMPLE IS EDITABLE

const series = [{
  data: [1, 2, 3]
}, {
  data: [5, 7, 11]
}, {
  data: [13, 17, 19]
}];

<Chart width={300} height={100} minY={0} series={series}>
  <Bars />
</Chart>;
```
