# Hotel Bookings Analysis & Prediction

This project involves predicting outcomes related to hotel bookings using machine learning. Multiple classification models are trained and evaluated to determine the most accurate one for predicting booking-related outcomes.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Models Used](#models-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

## Project Overview

This project uses machine learning to analyze hotel booking data and predict outcomes like booking cancellations. Several classifiers are tested, and their performance is evaluated based on precision scores.

## Data Source

The dataset contains several features including:
- Hotel type (`Resort Hotel`, `City Hotel`)
- Meal plan
- Market segment (e.g., `Direct`, `Corporate`, `Online TA`)
- Booking details like room type, deposit type, customer type, and reservation dates.

## Models Used

The following machine learning classifiers were tested:
1. **Decision Tree Classifier**
2. **Support Vector Classifier (SVC)**
3. **MLPClassifier (Multi-layer Perceptron)**

### Model Performance:
- **MLPClassifier** had the highest precision score, making it the best choice for this dataset.

## Project Structure

```bash
.
├── HotelBookings_Notebook.ipynb   # Main notebook for data analysis and model training
├── README.md                      # Documentation for the project
```

## Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `numpy`

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hotel-booking-analysis.git
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook HotelBookings_Notebook.ipynb
   ```

## Results

After evaluating multiple models, the **MLPClassifier** was found to deliver the highest precision score, making it the best model for predicting hotel bookings in this dataset.

## Future Improvements

- **Hyperparameter Tuning**: Further optimization of the `MLPClassifier` could yield even better performance.
- **Feature Engineering**: Adding more features or fine-tuning existing ones might improve model accuracy.
- **Visualization**: Include more visualizations to better understand feature importance and model behavior.

## License

This project is licensed under the MIT License.
