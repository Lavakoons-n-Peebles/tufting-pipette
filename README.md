# Tufting Pipette

**Tufting Pipette** is a web tool designed to simplify color palette management for tufting projects. It allows users to extract precise color schemes directly from reference images, ensuring your yarn selection perfectly matches your design.

[Live Tool: Lavakoons-n-Peebles/Tufting-Pipette](https://lavakoons-n-peebles.github.io/tufting-pipette/)

## Key Features

* **Smart Extraction:** Uses an advanced density-based algorithm to identify core colors while filtering out noise, shadows, and anti-aliasing artifacts.
* **Dynamic Analysis:** Automatically calculates color frequency to help you determine exact yarn ratios for your patterns.
* **Interactive Workflow:** Features a drag-and-drop sortable table to organize your palette, fields for custom yarn notes, and an integrated highlighting tool to preview color placement on your design.
* **Excel-Ready Export:** Export your complete palette in CSV or JSON formats with one click—perfect for seamless integration with Excel or Google Sheets.
* **Zero-Setup:** Runs entirely in your browser—no downloads or installations required.


## How to Use

1. **Upload:** Drag or select your design image to load it onto the canvas.
2. **Extract:** The tool automatically detects the primary colors. Use the **Search Depth** control to adjust the sensitivity for complex images.
3. **Refine:** Sort your rows to match your creative flow and use the highlighting feature to pinpoint exactly where each color appears in your design.

## Technical Details

Built using the **Canvas API** for performant pixel manipulation and **SortableJS** for an intuitive user experience. The application focuses on local processing to ensure privacy and speed.
