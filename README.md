Smart Price Comparator
======================

## Description
The **Smart Price Comparator** is a web-based application that helps users compare the unit price of different products. By entering each product’s brand, price, and quantity, the tool calculates the cost per unit, highlights the **Best Value** and **Next Best Value**, and shows how much money can be saved. Crucially, the results appear **in the same order** as they were entered, for maximum transparency and usability.

---

## Features
1. **Add and Remove Products**  
   Easily add or remove items as you compare different brands or products.

2. **Unit Price Calculation**  
   Automatically computes the unit price based on the product’s total price and quantity.

3. **Best Value & Next Best Value**  
   - Highlights the product(s) with the lowest unit price as **Best Value**.  
   - Identifies the **Next Best Value** (if applicable) and shows the difference in cost.

4. **Equal Unit Price Handling**  
   If multiple products share the same unit price, all of them are labeled as **Best Value**.

5. **Display Results in Input Order**  
   The comparison table follows the exact order in which products were added, ensuring clarity and fairness.

6. **Detailed Summary**  
   Provides a summary of the cheapest product(s), their total cost, and potential savings compared to the next best alternative.

7. **Modern, Responsive Design**  
   Uses HTML5, CSS3, and JavaScript to deliver a clean, user-friendly interface across all devices.

---

## How to Use
1. **Open `index.html`:**  
   - Download or clone the project from GitHub.  
   - Open `index.html` in any modern web browser.

2. **Enter Product Information:**  
   - **Brand:** Type the product or brand name.  
   - **Price:** Enter the total price (in THB).  
   - **Quantity:** Specify how many items or units are included.

3. **Manage Products:**  
   - **Add Product:** Click **"＋ เพิ่มสินค้า"** to include more items.  
   - **Remove Product:** Click the **"✕"** button beside an item to delete it.

4. **Calculate Results:**  
   - Click **"≡ คำนวณ"** to generate a comparison table.  
   - The tool displays each product’s unit price and labels the **Best Value** and **Next Best Value**.

5. **Analyze Summary:**  
   - A summary section describes the cheapest brand(s), total costs, and savings if a second-best product is identified.

6. **Interpret Savings:**  
   - If your chosen **Best Value** product is cheaper than the **Next Best Value**, the summary calculates how much you save per unit and overall.

---

## Installation
1. **Clone the Repository (Optional):**  
    ```bash 
    git clone https://github.com/witchakornb/Smart-Price-Comparator.git 

    cd Smart-Price-Comparator
    ```

2. **Open the Project:**  
- Locate the folder and open the `index.html` file in your web browser.

---

## Technologies Used
- **HTML5**: For structuring the page and input fields.  
- **CSS3**: For styling the layout, colors, and responsiveness.  
- **JavaScript**: For real-time calculations, DOM manipulation, and interactivity.

---

## Known Issues
- **Clipboard API**: Copying results to the clipboard may not work on some older browsers.  
- **Minimal Validation**: Basic checks are in place, but unexpected inputs may cause unusual behavior.

---

## Contributing
We welcome all contributions. To propose changes or additions:

1. **Fork the Repo**: Create your own copy of the project on GitHub.  
2. **Checkout a New Branch**:  
    ```bash
    git checkout -b feature/improve-comparison
    ```
3. **Implement Changes**: Add new features or fix existing issues.  
4. **Commit & Push**:  
    ```bash
    git commit -m "feat: add advanced validation for user inputs" git push origin feature/improve-comparison
    ```
5. **Open a Pull Request**: Submit your changes for review and discussion.

---

## License
This project is distributed under the [MIT License](https://opensource.org/licenses/MIT), which allows modification, distribution, and private or commercial use.

---

## Author
**WitchakornB**  
GitHub: [https://github.com/witchakornb/Smart-Price-Comparator](https://github.com/witchakornb/Smart-Price-Comparator)

---

## Acknowledgments
We appreciate the open-source community for providing resources and inspiration that made the **Smart Price Comparator** possible. If you find this tool useful, please consider starring the repository or sharing it with others who might benefit.
