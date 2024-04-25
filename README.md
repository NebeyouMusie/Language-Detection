# Language Detection
 - A language detection model is a type of artificial intelligence (AI) that can identify the language a piece of text is written in.  These models are often used in machine translation applications, where they can automatically determine the source language of a text so that it can be translated into the correct target language.  Language detection models can also be used to categorize and sort information, or to filter content based on language.
   
## What's its usecase?
 - Language detection models have a wide range of applications, here are some of the most common:
    - **Machine translation**:  By identifying the source language of text, translation services can automatically choose the right translation model for the job,  leading to more 
      accurate and relevant translations.
    - **Content management**:  Large organizations that deal with information in multiple languages can use language detection to automatically sort and categorize documents according to 
      the language they're written in. This makes it much easier to find specific information.
    - **Customer service**: Companies with a global customer base can use language detection to route customer inquiries to agents who speak the appropriate language. This improves 
      customer satisfaction and ensures that customers get the help they need quickly.
    - **Web search**: Search engines use language detection to ensure users get the most relevant results for their queries. By identifying the language a search term is in, the search 
      engine can return results in that language.  
    - Google Translate is one of the most popular language translators in the world which is used by so many people around the world. It also includes a machine learning model to detect 
      languages that you can use if you don’t know which language you want to translate.
 - So in this project we will see how you can train a Machine Learning model to detect a language

## Data Description
- I have used the `language.csv` file for the project
- The dataset contains two columns namely:
1. Text - sentence for the respective language
2. language - name of the language

## Algorithm Description
 - The algorithm I have used is Multinomial Naïve Bayes algorithm to train the language detection model as this algorithm always performs very well on the problems based on multiclass classification, you can check the model's training process in the `language-detection.ipynb` notebook

## Libraries Used
 - Numpy
 - Pandas
 - Scikit-learn

## Score
 - Score: 0.9416909620991254 (94%)

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: git clone https://github.com/NebeyouMusie/Language-Detection.git
 3. Create and Activate Virtual Environment (Recommended)
    - python -m venv venv
    - source venv/bin/activate
 4. Install Libraries: pip install numpy pandas scikit-learn
 5. Open `language-detection.ipynb` and run all cells
 6. Or you can download the `language.csv` and `language-detection.ipynb` file from the repository, upload those files to [Google Colab](https://colab.research.google.com/) then run all the cells in the `language-detection.ipynb` Notebook

## Acknowledgments
 - I would like to thank [Aman Kharwal](https://www.linkedin.com/in/aman-kharwal)
