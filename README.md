# Sales Summary App

This is a simple, single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display it prominently on the page. The application is built with a responsive design using Tailwind CSS.

## Features

*   **Data Fetching:** Automatically retrieves `data.csv` from the same directory.
*   **Sales Calculation:** Parses the CSV to sum all values in the 'sales' column.
*   **Dynamic Display:** Updates the page title and a dedicated `div` with the calculated total sales.
*   **Responsive Design:** Utilizes Tailwind CSS for a clean and mobile-friendly interface.

## How to Use

1.  **Save Files:** Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open `index.html`:** Simply open `index.html` in your web browser.
3.  **View Summary:** The application will automatically fetch `data.csv`, calculate the total sales, and display the sum on the page.

## `data.csv` Format

The `data.csv` file is expected to have a header row, and one of the columns must be named `sales` (case-insensitive).

**Example `data.csv`:**

```csv
id,product,sales,region
1,Laptop,1200.50,North
2,Mouse,25.00,South
3,Keyboard,75.25,East
```

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsiveness.
*   **JavaScript:** For fetching, parsing, and displaying data.

## Development

To develop or modify this application, you can directly edit `index.html`. The JavaScript logic is embedded within the HTML file for simplicity.