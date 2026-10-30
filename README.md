# Project Name: Oil Brent price per barrel evolution in 2026

**This project provides a visualization via an interactive OHLC chart that describes the evolution of the price of the Brent Barrel price during 2026**

---

## 🚀 Quick Start
You can run the data pipeline using firstly Google Colab to execute the Google Colab Jupyter Notebook and importing the data source file located in the folder data.
The Google Colab Jupyter Notebook will generate an html file index.html that will contain the output visualization.


## 📁 Repository Structure
* `data/` — Contains the raw dataset files (`.csv`).
* `OHLC_Brent_2026.ipynb` — Contains the Google Colab Jupyter Notebook (`.ipynb`) used for data processing and HTML generation.
* `index.html` — Contains the output `.html` visualization.

## 📊 Dataset Information
* **Source:** Google Finance BZW00:NYMEX  ([Link to source](https://www.google.com/finance/quote/BZW00:NYMEX))
* **Description:** This dataset contains the evolution of Oil Brent price per barrel for each week of 2026 including opening, minimum, maximum and closing price. The dataset also includes the transaction volume.

## 🛠️ Execution Guide
Follow these steps to run the pipeline and generate the HTML file:

1. **Open the Notebook:** Import the notebook to Google Colab and open the notebok.
2. **Run All Cells:** Execute the cells sequentially by pressing `Runtime` > `Run all` in the top menu.
3. **Fetch the Data:** The notebook will ask to upload the data file, make sure you download it from the `data/` folder in the repository.
4. **Generate the HTML:** The final cell generates the processed visualizations into a standalone HTML file, which will automatically download to your local machine.

## 🖥️ View the Result
If you just want to see the final output without running any code:
* Download the `index.html` file and open it in any web browser.
* [Optional] View the live interactive version directly on [GitHub Pages](https://victorcalvo25.github.io/brent-ohlc-2026/).
