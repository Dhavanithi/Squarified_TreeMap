# Squarified Treemap Visualization

## Overview

The **Squarified Treemap Visualization** is a web-based data visualization project that represents hierarchical data using the Squarified Treemap layout algorithm. The application displays corporate budget distribution by dividing the available display area into rectangles, where each rectangle represents a department, category, or sub-category, and its size is proportional to the allocated budget. The Squarified Treemap algorithm minimizes extreme aspect ratios, resulting in balanced, readable, and space-efficient visualizations.

The project is developed using **HTML5, CSS3, JavaScript (ES6), and the HTML5 Canvas API**. The application dynamically loads hierarchical data from a JSON file, computes parent node values recursively, and renders the treemap with distinct colors, labels, and budget values. The visualization provides a clear understanding of budget allocation across multiple organizational levels.

## Features

* Visualizes hierarchical corporate budget data using the Squarified Treemap algorithm.
* Dynamically loads budget information from an external JSON file.
* Calculates parent node values recursively from child nodes.
* Optimizes rectangle aspect ratios for improved readability.
* Displays department names and allocated budget values within each treemap block.
* Uses different color palettes to distinguish organizational categories.
* Automatically wraps long labels inside treemap rectangles.
* Provides a clean, modern, and responsive interface using HTML5 Canvas.
* Implements recursive rendering for unlimited hierarchical levels.
* Lightweight implementation without using external visualization libraries.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* HTML5 Canvas API
* JSON

## Working Principle

The application begins by loading hierarchical corporate budget data from the **data.json** file. Each parent node's total budget is calculated recursively by summing the values of its child nodes. The Squarified Treemap algorithm then computes an optimized layout where the available canvas area is divided into rectangles proportional to each node's budget while maintaining near-square aspect ratios for better visualization.

The layout is rendered recursively on the HTML5 Canvas. Parent categories are displayed with colored headers, while leaf nodes are filled with different colors and labeled with their respective department names and budget values. Text wrapping is applied automatically to ensure readability within smaller rectangles.

## Applications

* Corporate Budget Analysis
* Financial Data Visualization
* Business Intelligence Dashboards
* Organizational Resource Allocation
* Hierarchical Data Representation
* Educational Demonstrations of Treemap Algorithms
* Data Analytics and Reporting Systems

## Advantages

* Efficient representation of hierarchical datasets.
* Optimized rectangle layout improves readability.
* Makes large datasets easier to analyze visually.
* Lightweight and fast rendering using Canvas.
* Easy to customize with different datasets and color themes.
* Does not require external visualization frameworks.

## Future Enhancements

* Interactive zooming into treemap nodes.
* Tooltip display with detailed budget information.
* Search and filter functionality.
* Responsive canvas resizing for different screen sizes.
* Export visualization as PNG or PDF.
* Dark and Light theme switching.
* Animated transitions while loading data.
* Support for multiple hierarchical datasets.

## Conclusion

The **Squarified Treemap Visualization** project demonstrates an efficient method for representing hierarchical corporate budget data through optimized space utilization and clear visual organization. By combining recursive algorithms, HTML5 Canvas rendering, and dynamic JSON data loading, the application provides an intuitive and visually appealing solution for analyzing budget allocation across different organizational levels. The project highlights the practical use of treemap algorithms in financial analysis, business intelligence, and hierarchical data visualization.

## Output

<p align="center">
  <img src="C:\Users\Admin\OneDrive\Documents\OneDrive\Pictures\Screenshots" alt="Squarified Treemap Output" width="1000"/>
</p>
