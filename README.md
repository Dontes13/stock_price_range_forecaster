# Stock Price Range Forecaster (GRU vs LSTM)

Stock market forecasting plays a vital role in helping investors and analysts make informed decisions. In this project, we focus on predicting the **next-day high–low price range** of a stock using deep learning sequence models. We compare **Gated Recurrent Unit (GRU)** and **Long Short-Term Memory (LSTM)** architectures to determine which model better captures time series patterns in stock price data.

Our pipeline ensures fair comparison by using the same preprocessing, feature set, and evaluation metrics for both models.  
Developed as part of the **AI4ALL Summer Program**.

---

## Our Team 🚀
**Dante Santurian** – University of Michigan  
<!-- Add any teammates here if applicable -->

---

## Features

**Implementation of Deep Learning Models:**  
Jupyter Notebook showcasing GRU and LSTM architectures for range prediction.

**Consistent Preprocessing & Fair Comparison:**  
Sliding window sequence generation, normalization, and identical train/validation/test splits.

**Evaluation Metrics:**  
MAE (Mean Absolute Error) and RMSE (Root Mean Square Error) to measure predictive accuracy.

**Result Visualizations:**  
Clear and interpretable charts comparing GRU vs LSTM performance.

**Reproducible Pipeline:**  
Easy-to-run code that generates metrics and visualizations from raw OHLCV data.

---

## Getting Started
Clone the repo and install required dependencies with pip.

```bash
pip install -r requirements.txt
```

---

## Usage/Examples

- **Run the notebook:** Open `forecasting_notebook.ipynb` in your preferred environment (e.g., Google Colab, Jupyter Lab, Jupyter Notebook, VS Code).

- **Examine the results:** The notebook contains detailed explanations and markdown to guide you through each step, including data preparation, training, evaluation, and visualizations of GRU vs LSTM performance. You can run the cells sequentially to reproduce our results, which are displayed directly in the notebook outputs.

- **Modify for your use case:** Adapt model parameters (e.g., window size, features, hidden units) to suit different training scenarios and datasets.

---

## Future Directions

**Experiment with Different Architectures**  
Explore alternative time series models such as Temporal Convolutional Networks (TCNs) or Transformers, and optimize hyperparameters to identify a model that balances accuracy and efficiency.

**Implement Feature Expansion**  
Incorporate technical indicators, sentiment analysis, or macroeconomic data to improve predictive performance.

**Deploy as a Web App**  
Create an interactive dashboard or API for real-time stock range predictions.

---

## Project Artifacts
- **Project Proposal**: *link here*  
- **Final Presentation**: *link here*  
- **Project Poster**: *link here*

---

## Thank You 🙏
A big thank you to our AI4ALL instructors and mentors for their guidance and feedback throughout the program. Their support was crucial in shaping this project and helping us achieve our goals.
