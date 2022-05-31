
If I've done everything correctly, the following div should render as a graph.


<div class="kg-container">
params: 
    - {name: m, value: 1, min: -2, max: 2, round: 0.01}
layout:
  OneGraph:
    graph:
      objects:
      - Line:
          point: [0,4]
          slope: params.m
          drag: 
            - directions: y
              param: m
              expression: "(drag.y - 4)/drag.x"
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
