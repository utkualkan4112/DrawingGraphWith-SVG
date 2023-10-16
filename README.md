# DrawingGraphWith-SVG

# Dynamic SVG Graph Representation: Suicide Rates in Turkey (2009-2022)

## Abstract
This project explores the dynamic creation of Scalable Vector Graphics (SVG) for data representation, focusing on suicide rates in Turkey from 2009 to 2022. Leveraging inline JavaScript for generating SVG elements, the visualization offers a clear, insightful representation of the statistical data.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [SVG Creation](#svg-creation)
  - [Graph Components](#graph-components)
- [Data Representation](#data-representation)
  - [Scaling and Layout](#scaling-and-layout)
  - [Iteration and Drawing](#iteration-and-drawing)
  - [Annotation and Styling](#annotation-and-styling)
- [Challenges & Solutions](#challenges--solutions)
- [Conclusion](#conclusion)

## Introduction
This project aimed to create an interactive graphical representation of sensitive data concerning the suicide rates in Turkey over a span of 13 years. The challenge was to accurately and respectfully visualize this data, using JavaScript functions to generate various SVG elements dynamically.

## Methodology

### SVG Creation
The initial phase involved setting up the environment for SVG elements to be displayed. This setup included creating a foundational SVG element and establishing a viewport within which all graphical components would be contained.

### Graph Components
The project makes use of three distinct functions, each responsible for rendering specific SVG elements essential to the graph's construction:
- **Rectangles:** Utilized for crafting the bars of the graph, with parameters for x, y coordinates, width, height, and color. A rotation transformation was applied where necessary.
- **Lines:** Employed for the grid of the graph and connecting data points, requiring the start and end coordinates.
- **Text:** Used for labeling, incorporating parameters for the content, positioning, rotation, and font styling.

## Data Representation

### Scaling and Layout
A critical aspect was the logical scaling on the Y-axis, ensuring the graph's maximum limit encapsulated the highest suicide count recorded. The decision was made to set this limit at 5000, correlating to 200 units in the SVG system. Further, a consistent spacing of 30 units was established between columns for clarity.

### Iteration and Drawing
The drawing mechanism iterated over the data, creating a corresponding rectangle for each entry. A significant adjustment was the 180-degree rotation of the rectangles to combat the SVG's default inverted orientation.

### Annotation and Styling
Additional elements, such as lines and text labels, were anchored to the rectangles. Specific annotations, including the year and suicide count, were rotated for optimal space utilization and readability.

## Challenges & Solutions
- **Orientation:** The default downward direction of the rectangles was counterintuitive, resolved by implementing a calculated rotation.
- **Data Integration:** The initial plan considered integrating external data files, but the streamlined approach of using hardcoded data proved more efficient.
- **Scaling:** Ensuring the visual integrity of the data representation required meticulous attention to the proportional scaling between the SVG elements and the actual data.

## Conclusion
This project underscores the powerful capability of dynamic SVG elements in creating meaningful, accurate data visualizations. Through innovative problem-solving and technical adjustments, the graph successfully mirrors the sobering reality of the data it represents, providing a platform for further discussion and analysis.

---
For any additional information or queries regarding the project, please feel free to open an issue or contact [your GitHub handle or email].

 
