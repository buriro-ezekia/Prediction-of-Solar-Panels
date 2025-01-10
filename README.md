# Solar Panels Import Forecasting

## Objective
The objective of this project was to predict annual imports of solar panels, specifically focusing on three key variables:
1. **Quantity** (number of units)
2. **Weight** (in kilograms)
3. **Custom Value** (in Tanzanian Shillings)

The predictions covered a period from the year 2025 to 2074.

## Scope
To achieve the objective, the project encompassed the following tasks:
1. **Data Collection and Preparation**: Used historical data on solar panel imports, including the quantity, weight, and custom value for each year.
2. **Feature Engineering**: Create relevant features that can improve the predictive power of the models. For example, the value per kilogram (value_per_kg) can be derived from the custom value and weight.
3. **Model Training**: Trained machine learning models to predict each of the target variables:
   - **Quantity**: Random Forest Regressor
   - **Weight**: Gradient Boosting Regressor
   - **Custom Value**: Gradient Boosting Regressor
4. **Model Validation**: Validate the models using metrics such as the Mean Absolute Error (MAE) to ensure their accuracy and reliability.
5. **Future Predictions**: Used the trained models to predict the annual imports from 2025 to 2074. Ensured that the predictions are dynamic and reflect realistic trends over time.
6. **Visualization and Reporting**: Visualized the prediction results and provided a comprehensive report on the findings.

## Key Variables
- **Quantity**: The total number of units imported annually.
- **Weight**: The total weight of the imports in kilograms.
- **Custom Value**: The total value of the imports in Tanzanian Shillings.

## Installation and Usage
To run the predictions, follow these steps:

1. **Clone the Repository**
   ```shell
   git clone https://github.com/buriro-ezekia/solar-panels-import-forecasting.git
   cd solar-panels-import-forecasting
   ```

2. **Install Dependencies**
   Ensure you have Python installed. Then, install the required packages:
   ```shell
   pip install -r requirements.txt
   ```

3. **Prepare the Data**
   Place the historical import data in the `data` folder. Ensure the data is formatted correctly, with columns for `date`, `quantity`, `weight_kgs`, and `custom_value_tshs`.

4. **Run the Forecasting Script**
   ```shell
   python forecast.py
   ```

5. **View the Results**
   The predictions will be saved in a CSV file named `Predicted_Solar_Panels_Values_2025_2074.csv` in the `output` folder.

## Project Structure
- `data/`: Folder to store the input data files.
- `output/`: Folder to store the prediction results.
- `forecast.py`: Main script to run the forecasting models.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation (this file).

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or further information, please contact Buriro Ezekia (ezekia.buriro1810@gmail.com).

---

Thank you for your interest in this project! We hope it provides valuable insights into the future of solar panel imports.
