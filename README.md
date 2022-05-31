
If I've done everything correctly, the following div should render as a graph.


<div class="kg-container">
  
layout:
  OneGraph:
    graph:
      objects:

      # Point object at coordinates (6,4)
      - Point:
          coordinates: [6,4]

      # Red point object at coordinates (3,3)
      - Point:
          coordinates: [3,3]
          color: red

</div>
