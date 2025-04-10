# Route-Optimization-with-Map-Visualization
This project demonstrates a simple yet powerful route optimization and visualization solution using Python and Plotly. It highlights optimal paths between nodes and presents them on an interactive map with color-coded markers and routes.

**📌 Features**
Visualizes routes between start and end locations on a Mapbox map

Draws blue lines between all route segments

Marks static route nodes with black points

Highlights the starting node with a red marker

Highly interactive: zoom, pan, and explore the map in detail

**📊 Requirements**

Python 3.7+

Jupyter Notebook / Jupyter Lab

Libraries:

pandas

plotly

**📌 How It Works**

Loops through each row of the DataFrame

Draws lines from (start_x, start_y) to (end_x, end_y)

Plots all start nodes as black markers

Plots the first starting node in red

**💡 Future Improvements**

Integrate Dijkstra or OR-Tools for dynamic path optimization

Animate vehicle movement along the route

Add travel time and distance labels on the path
