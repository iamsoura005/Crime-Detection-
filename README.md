

# Crime Detection & Hotspot Mapping

A predictive analytics tool designed to forecast crime occurrences and identify high-crime areas (hotspots) across Indian districts using historical data.

## 📌 Objective

The primary goal of this project is to:

* Predict the total number of crimes in Indian districts.
* Identify and map high-crime (hotspot) areas.

This is achieved by analyzing the "Crime in India" dataset, focusing on major crimes such as murder, robbery, burglary, theft, and rape.

## 📊 Dataset

* **Source**: [Crime in India Dataset](https://www.kaggle.com/datasets/rajanand/crime-in-india)
* **File Used**: `01_District_wise_crimes_committed_IPC_2001_2012.csv`
* **Features**: District-wise crime statistics from 2001 to 2012.

## 🛠️ Tools & Technologies

* **Platform**: Google Colab
* **Data Handling**: pandas
* **Machine Learning**: scikit-learn

  * Linear Regression for crime prediction
  * K-Means Clustering for hotspot identification
* **Visualization**: seaborn, matplotlib([github.com][1])

## 📁 Project Structure

* `Crime Predictive Model.ipynb`: Jupyter Notebook containing data preprocessing, model training, prediction, and visualization steps.
* `README.md`: Project overview and instructions.([github.com][1], [github.com][2])

## 🚀 Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/iamsoura005/Crime-Detection-.git
   cd Crime-Detection-
   ```
2. **Open in Google Colab**:

   * Upload the `Crime Predictive Model.ipynb` notebook to Google Colab.
3. **Install Dependencies**:

   * Ensure the following Python libraries are installed:

     ```python
     pip install pandas scikit-learn seaborn matplotlib
     ```
4. **Run the Notebook**:

   * Follow the cells sequentially to preprocess data, train models, and visualize results.([github.com][2])

## 📈 Results

* **Crime Prediction**:

  * Utilized Linear Regression to forecast crime rates based on historical data.
* **Hotspot Mapping**:

  * Applied K-Means Clustering to identify districts with high crime rates.
  * Visualized hotspots using scatter plots and heatmaps.

## 📌 Future Enhancements

* Incorporate more recent data for improved accuracy.
* Explore advanced machine learning models for better predictions.
* Integrate geospatial analysis for more detailed hotspot mapping.

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance the project or add new features, feel free to fork the repository and submit a pull request.

## 📬 Contact

For any queries or suggestions, please open an issue in the repository.

