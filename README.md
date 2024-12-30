# Translation EDA/Visualization
## Dataset
The dataset used in this project is a CSV file containing translation data between English and Arabic. The file includes the following columns:

* english: Translated English text
* arabic: Translated Arabic text
  
## Notebook Overview
This notebook performs Exploratory Data Analysis (EDA) and data visualization on the translation dataset. Below is an outline of the steps included:

### Libraries and Dependencies
The following libraries and tools are used:

* NLTK: Natural Language Toolkit for text processing.
* TextBlob: Simplified text processing library for sentiment analysis.
* Arabic-Reshaper and Python-Bidi: For proper rendering of Arabic text.
* Pandas: For data manipulation and analysis.
* Matplotlib and Seaborn: For static data visualization.
* Plotly: For interactive visualizations and word clouds.

### Steps in the Notebook
1. Data Loading: The dataset is loaded into a Pandas DataFrame from the CSV file. The data is then prepared for analysis.

2. Exploratory Data Analysis (EDA):

   * Frequency Analysis: Calculation and display of the frequency of each unique value in both the English and Arabic columns.
   * Distribution of Character Lengths: Visualization of the distribution of character lengths for both languages.
   * Length Comparison: Scatter plot comparing the lengths of English and Arabic text.
   * Word Frequency: Identification of the 30 most frequently occurring words in both English and Arabic using CountVectorizer.
   * Word Clouds: Visualization of the most common words in both languages.
     
3. Sentiment Analysis:
   * Distribution of Sentiment Polarity: Analysis of the sentiment polarity distribution for both English and Arabic text.

### Usage
1. Install the required libraries:

        pip install nltk textblob arabic-reshaper python-bidi matplotlib seaborn plotly
2. Download necessary resources:
   
        python -m textblob.download_corpora
3. Run the notebook: Open the notebook in a Jupyter environment or colab and execute the cells to perform EDA and visualize the data.
   
* For accurate rendering of Arabic text in word clouds, an Arabic font file (NotoNaskhArabic-Regular.ttf) is required.
