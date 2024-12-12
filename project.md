# Projects

---

## **Wikipedia Adminship Requests: Graphical, Temporal & Thematical Data Analysis**

### **Project Overview**
This project explores the dynamics of the Request for Adminship (RfA) process on Wikipedia. Using a dataset of votes cast between 2003 and 2013, we analyzed voting patterns and outcomes to uncover insights into the governance mechanisms of Wikipedia.  

**Key Data Points**:  
- **Votes analyzed**: 198,275 across 189,004 unique voter-votee pairs.  
- **Users involved**: 11,381.  
- **Categories extracted**: Top 10 most edited pages per user for context.  

### **Key Insights**
- **Voting is advisory**: Bureaucrats make final decisions based on support ratio, comments, and user behavior.  
- **Success rates over time**: The likelihood of adminship has declined, indicating stricter standards.  
- **Influential voters**: Some community members consistently impact voting outcomes.  

### **Interactive Results**
Explore more about voting patterns, success rates, and community dynamics:  
[View Project Results](https://epfl-ada.github.io/ada-2024-project-supercoolteamname2024/)

**Authors**: *Tallula Graber, Benoit Matthey-dit-Doret, Malen Raychev, Edouard Bueche, Gal Pascual*

---

## **Sentiment Analysis on Reddit for Stock Market Predictions**

### **Abstract**
This project investigates whether Reddit sentiment can predict stock returns. By analyzing comments from 13 subreddits in 2021, we calculated sentiment scores using NLP techniques and applied machine learning models to evaluate predictive potential.

**Key Data Points**:  
- **Comments analyzed**: 500,000+  
- **Labeled comments**: 3,500 (specific to Tesla, S&P 500, and other major stocks).  
- **Sentiment tools**: VADER, TextBlob, GPT-3.5-turbo.

### **Methodology**
1. **Data Preprocessing**: Cleaned noisy data and labeled stock-specific comments using GPT-3.5-turbo.  
2. **Sentiment Analysis**: Used NLP models to assign sentiment scores to each comment.  
3. **Machine Learning Models**: Applied Random Forest, LSTM, and Gradient Boosting to predict stock returns.

### **Key Findings**
- **Correlation**: Weak overall correlation between sentiment and stock returns (e.g., 0.15 for S&P 500).  
- **Model Performance**:  
  - **Random Forest**: Best performance with 67.21% directional accuracy for Tesla (GPT sentiment).  
  - **LSTM**: Effective for time-series data but resource-intensive.  
  - **Gradient Boosting**: Moderate performance (57.38% directional accuracy for S&P 500 with TextBlob).  

### **Conclusion**
Sentiment analysis shows potential but needs integration with other financial indicators. Data sparsity and methodology refinement are critical for improved outcomes.

**Full Report**:  
[Download Report (PDF)]({{ site.baseurl }}/assets/files/Reddit_Sentiment_Analysis.pdf)

**Authors**: *Edouard Bueche, Yassine Ben Said, Pierre Porchet*

---

## **Detection of Short-Lived Market Bubbles Using Big Data**

### **Overview**
This project investigates the phenomenon of short-lived market bubbles through predictive modeling and big data analysis. Using a combination of numerical data and natural language processing (NLP) techniques, we explored patterns and indicators of market anomalies.

### **Key Insights**
- Developed predictive models to detect short-lived financial trends.  
- Combined numerical and sentiment data from financial subreddits.  
- Highlighted limitations in data volume and predictive accuracy.  

**Learn More**:  
[See the Report (PDF)]({{ site.baseurl }}/assets/files/ML_project.pdf)

**Authors**: *Edouard Bueche*

---
