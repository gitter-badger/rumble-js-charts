```
const series = [{
    data: [1, 2, 3]
}, {
    data: [5, 7, 11]
}, {
    data: [13, 17, 19]
}];

<Chart width={300} height={100} series={series} minY={0}>
  <Layer width='95%' height='85%' position='center bottom'>
    <Dots />
    <Labels 
      label={({point}) => ('y=' + point.y)}
      dotStyle={{
        textAnchor: 'middle',
        alignmentBaseline: 'after-edge',
        fontFamily: 'sans-serif',
        fontSize: '0.65em'
      }}
      labelAttributes={{
        y: -4
      }}
    />
  </Layer>
</Chart>
```
