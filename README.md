## How to Run

1. Download or clone this repository.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `main.ipynb` in VS Code or Jupyter Notebook.
4. Run all cells from top to bottom.

The program reads sales data from the `data/` folder and generates two files in the `output/` folder:

- `cleaned_orders.csv` — Cleaned sales records.
- `sales_by_product.csv` — Sales summary by product.

## Expected Results

The sample dataset contains 11 unique orders after removing duplicates.

Total sales: **490 THB**.
