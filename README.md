# Analysis of Newspaper Propaganda Biases

We present a system which visualizes newspaper biases on the basis of propaganda techniques using PRTA API. The system is an umbrella containing two applications, a JS frontend powered by d3.js and a flask backend.

The JS frontend can be hosted on a simple live server. We recommend a VS code live server or a live python http server using
```sh
python3 -m http.server [PORT NUMBER]
```

For BE, the following packages need to be installed:<br/>
 - flask
 - flask-cors
 - numpy
 - pandas
 - scikit-learn
 - scipy
 - spacy
 - nltk
 
Spacy and NLTK require further packages which can be installed by running
```sh
python -m spacy install en_core_web_sm
python -m nltk install stopwords
```
To run BE, run
```sh
flask run
```
The backend abstracts the following APIs
 - /<search_criteria>
 - /article/<article_id>

## Files

Kaggle Dataset: https://www.kaggle.com/snapcrack/all-the-news
Original Kaggle data of the "All the News" dataset are the files: `articles1.csv`, `articles2.csv` and `articles3.csv`

Install the data files and store them in a directory named 'archive' in the project directory.
With this, you are all set!

Cheers!
