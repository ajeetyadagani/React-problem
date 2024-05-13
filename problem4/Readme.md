The Gallery component accepts children as its prop. It renders these children inside a div with a grid layout using CSS grid.
Each child element (in this case, Image components) is displayed within the grid layout, and the layout adjusts dynamically based on the number of children.
The Image component is a simple functional component that renders an img element with the provided src.
Inline styles are used to style the grid layout and images for simplicity.
You can include additional Image components as children of the Gallery component to simulate a dynamic gallery where images can be added or removed as needed.