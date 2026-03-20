# Flex Boots Calculator

A lightweight, zero-dependency web application that automatically calculates the required sizes and quantities of neoprene gaiters and back straps based on a customer's boot order. 

This project converts a static spreadsheet matrix into an interactive, client-side calculator.

## Features
* **Instant Calculation:** Uses Vanilla JavaScript to update required parts in real-time as users input boot quantities.
* **Zero Dependencies:** Built entirely with standard HTML, CSS, and JS. No build steps, package managers, or frameworks required.
* **Hardcoded Matrix:** The mapping of boot sizes to accessory sizes (XS, S, M, L, XL) is safely hardcoded into the script, preventing accidental user edits.

## Usage
1. Open `index.html` in any modern web browser.
2. Enter the desired quantity next to the corresponding boot size in the main table.
3. The top summary tables will automatically aggregate the total required neoprene gaiters and back straps by size.
4. To reset the calculator, clear or zero out the input fields.

## Deployment 
This application is a static site and can be hosted for free using GitHub Pages.

1. Ensure `index.html` is in the root of your repository.
2. Navigate to your repository **Settings** on GitHub.
3. Select **Pages** from the left-hand sidebar.
4. Under **Build and deployment**, set the Source to **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. GitHub will provide a live URL (e.g., `https://[your-username].github.io/[repo-name]`) within a few minutes.

## File Structure
* `index.html`: Contains the markup, CSS styling, and JavaScript logic.
