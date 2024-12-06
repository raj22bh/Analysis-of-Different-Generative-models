# AI Model Analytics Dashboard

This project visualizes analytics data for five AI models: ChatGPT, Claude, Gemini, Perplexity, and Meta AI. The dashboard showcases usage trends, retention rates, churn rates, A/B testing results, and other insights into model performance and user feedback.

---

## Features

1. **Data Overview**: 
   - Includes key metrics like usage frequency, satisfaction scores, accuracy, retention, and churn rates.
   - Captures primary use cases, feedback topics, and recommended improvements for each model.

2. **Visualization Highlights**:
   - **Bar Chart**: 
     - Displays usage frequency by model.
   - **Pie Charts**: 
     - Highlights retention and churn rates for each model.
   - **Line Graph**:
     - Compares performance improvements between Version A and Version B during A/B testing.

3. **Insights**:
   - Customer behavior and feedback are analyzed for each model.
   - Roadmap impact reports offer a glimpse into planned improvements.

---

## Dataset

The data is stored in a pandas DataFrame with the following columns:

- `Model Name`: Name of the AI model.
- `Usage Frequency`: Daily usage frequency.
- `Satisfaction Score`: User satisfaction ratings (out of 5).
- `Accuracy Score`: Percentage accuracy.
- `Primary Use Case`: The primary application area for the model.
- `Retention Rate`: Percentage of users retained.
- `Churn Rate`: Percentage of users leaving.
- `Primary Feedback Topics`: Key topics of feedback from users.
- `Recommended Improvements`: Areas suggested for improvement.
- `A/B Testing Results`: Summary of A/B test outcomes.
- `Customer Behavior Insights`: Key user behavior observations.
- `Roadmap Impact Reports`: Planned enhancements and updates.

---

## Requirements

To run this project, you need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:

pip install pandas matplotlib seaborn  exit



 # **Usage
Clone the repository or copy the script.
Ensure the required libraries are installed.
Run the Python script to visualize the data:
Bar chart showing usage frequency.
Pie charts for retention and churn rates.
Line graph comparing A/B testing performance.

# **Insights
ChatGPT has the highest usage frequency and focuses on general Q&A.
Meta AI leads in retention rate and excels in creative writing with a high satisfaction score.
Claude shows impressive contextual understanding, reflected in retention rates and user feedback.

# *License
This project is licensed under the MIT License. See the LICENSE file for details.
