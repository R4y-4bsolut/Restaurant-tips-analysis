# 🍽️ Restaurant Tips Analysis

This project analyzes a dataset of restaurant tips to uncover patterns in tipping behavior based on factors such as time of day, day of the week, and meal type. It uses Python (Pandas, Matplotlib) to conduct exploratory data analysis and statistical testing.

![Analysis Preview](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/preview_image.jpg) <!-- replace or remove if needed -->

## 📊 Dataset

The dataset is loaded from a public source:
- URL: `https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv`
- Contains data such as:  
  - Total bill
  - Tip amount
  - Gender
  - Smoking status
  - Day
  - Time (Lunch/Dinner)
  - Party size

## 🔍 Key Questions Explored

- Do people tip more on weekends than weekdays?
- Does dinner generate higher tips than lunch?
- Are there significant differences in tipping behavior across genders or party sizes?

## 🛠️ Tools Used

- **Python**
- **Pandas** for data handling
- **Matplotlib** for visualization
- **Statistical tests** (e.g., t-tests) for hypothesis testing

## 🧪 Statistical Results Example

- **H₀**: Weekend tips are higher than weekday tips  
  - **p-value**: 0.9753 → _Fail to reject H₀_ (no significant difference)
  
- **H₀**: Dinner tips are higher than lunch tips  
  - **p-value**: 0.0144 → _Reject H₀_ (dinner tips are significantly higher)

## ▶️ How to Run

1. Clone the repository or download the notebook.
2. Open `Restaurant_tips_analysis.ipynb` in Jupyter Notebook or VSCode.
3. Run each cell in order to reproduce the analysis.

## 📂 File Structure
