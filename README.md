# Invoice Generation System

## Description
This project is aimed at automating the process of invoice generation using Selenium in Python. It interacts with a login page (`login.html`) and a simulated invoice generation form (`index.html`). The data for generating invoices is sourced from an Excel file (`NotasEmitir.xlsx`). The primary purpose is to mimic the workflow on a real website and streamline the invoice generation process.

## Project Structure
- **login.html:** This page simulates the login process to access the system.
- **index.html:** A simulated page for invoice generation used for development and training purposes.
- **NotasEmitir.xlsx:** An Excel file serving as the database for invoice generation.
- **EmissaoNotaFiscal.ipynb:** Jupyter Notebook containing the Python script for automating the invoice generation process using Selenium.

## Requirements and Setup
- Ensure that Python and Jupyter Notebook are installed in your environment.
- Install the necessary dependencies using `pip install selenium pandas webdriver-manager`.
- ChromeDriver must be installed and configured. You can download it [here](https://sites.google.com/chromium.org/driver/).

## Usage
1. Clone the repository: `git clone https://github.com/your-username/invoice-generation.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute the Jupyter Notebook file `EmissaoNotaFiscal.ipynb` to initiate the invoice generation process.

## Selenium Environment Configuration
The script is configured to download invoices to a specific directory. Adjust the download path in `options.add_experimental_option("prefs", {...})` as per your preferences.

## Contribution
Contributions are encouraged! Please refer to the [contribution guidelines](CONTRIBUTING.md) before making any changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

---

Feel free to customize the user information, such as `your-username`, and modify any project-specific details or team information. If you don't have a `CONTRIBUTING.md` or `LICENSE` file, you can remove them or add relevant information as needed.
