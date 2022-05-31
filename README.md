
If I've done everything correctly, the following div should render as a graph.


<div class="kg-container">
params:
- {name: theta, value: 0.78, min: -6.28, max: 6.28, round: 0.01}

calcs:
  x: "(5 + 3*(cos(params.theta)))"
  y: "(5 + 3*(sin(params.theta)))"
  
layout:
  OneGraph:
    graph:
      objects:
      - Circle: {coordinates: [5,5], r: 3}
      - Angle:
          showSegments: true
          pointA: {coordinates: [8,5], show: false}
          pointB: {coordinates: [5,5], show: false}
          pointC:
            coordinates: [calcs.x, calcs.y]
            drag:
            - directions: xy
              param: theta
              expression: atan2(drag.y-5,drag.x-5)
</div>


Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
Lorem ipsum dolor est.
