# Learning CSS Pseudo Selectors by Building a Balance Sheet

This project is a simple HTML/CSS webpage that simulates a balance sheet for a fictional company, AcmeWidgetCorp. It serves as an exercise to learn and apply CSS pseudo-selectors to style elements efficiently and accessibly. 

## Project Overview

The balance sheet displays company assets, liabilities, and net worth over three consecutive years (2019, 2020, and 2021). The main goal of this project is to use CSS pseudo-selectors to highlight different parts of the table, making the information visually organized and improving the user interface and accessibility.

## Features

- **Tables for Assets, Liabilities, and Net Worth**: Each table represents different financial categories.
- **Hover Descriptions**: Details about each row are shown with hover descriptions for better clarity.
- **Year Highlights**: The most recent year is highlighted to draw attention to the current values.
- **CSS Pseudo-Selectors**: Styled with `:hover`, `:first-child`, `:last-child`, and other pseudo-selectors to create an intuitive and accessible layout.

## How to Use

1. **Clone the Repository**  

2. **Open the Project**  
   Open the `index.html` file in a web browser to view the balance sheet layout.

## Files

- **index.html**: The HTML structure of the balance sheet, containing three tables.
- **styles.css**: The CSS stylesheet that applies various styles, including pseudo-selectors for enhanced user interaction and design consistency.

## Key Learning Points

- **CSS Pseudo-Selectors**:
  - `:hover`: Used for interactive elements to display additional information.
  - `:first-child`, `:last-child`, and similar selectors help apply styles based on element position.
- **ARIA Attributes**:
  - `aria-hidden="true"` is used for decorative or non-essential elements to improve accessibility.
- **Flexbox Layout**: Used for flexible positioning and layout adjustments across the document.
  
## Example Pseudo-Selector Usage

Below are a few examples of how pseudo-selectors are applied in this project:

```css
/* Highlight the current year column */
.current {
  font-weight: bold;
  color: #333;
}

/* Show description on hover */
.description:hover {
  color: #007acc;
}
```

## License

This project is open-source and available for free under the MIT License.

---

Feel free to modify the content based on the actual styling and additional features in your CSS file. Let me know if you'd like more details on any section!
