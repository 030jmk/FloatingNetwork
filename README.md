# Floating Network Background

A simple, lightweight HTML page featuring a dynamic background visualization of floating nodes connected by lines, overlaid on a vibrant gradient background.

## Features

*   Interactive floating nodes with random movement.
*   Lines connecting nearby nodes, with opacity based on distance.
*   Customizable node count and maximum connection distance via URL parameters.
*   Responsive design for various screen sizes.
*   Ability to set main heading and paragraph text via URL parameters.
*   Sleek gradient background.

## How to Use

1.  Clone or download the repository.
2.  Open the `index.html` file in your web browser.

### Customization via URL Parameters

You can customize the visualization and content by adding parameters to the URL:

*   `?h1=Your%20Heading`: Sets the main heading text. Replace `Your%20Heading` with your desired text (use `%20` for spaces).
*   `?p=Your%20Paragraph`: Sets the paragraph text. Replace `Your%20Paragraph` with your desired text.
*   `?nodeCount=150`: Sets the number of nodes. Replace `150` with your desired number.
*   `?maxDistance=250`: Sets the maximum distance between nodes for a line to be drawn. Replace `250` with your desired distance in pixels.

You can combine parameters using `&`:
`network.html?h1=Welcome&p=Check%20this%20out&nodeCount=100&maxDistance=200`

## Technologies Used

*   HTML5
*   CSS3
*   JavaScript (Canvas API)

## Potential Improvements

*   Add more color options for nodes and lines.
*   Implement performance optimizations for a very large number of nodes.
*   Introduce more interactive features (e.g., mouse interaction).
