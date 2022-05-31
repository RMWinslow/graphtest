
If I've done everything correctly, the following div should render as a graph.


<div class="kg-container">
  
params:

- name: blueX    # x-coordinate of blue point
  value: 6

- name: redY     # y-coordinate of red point
  value: 3
  min: 2
  max: 6
  round: 0.25
    
layout:
  OneGraph:
    graph:
      objects:
      - Point:
          coordinates: [params.blueX, 4]
          draggable: true
      - Point:
          coordinates: [3, params.redY]
          color: red
          draggable: true

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
