# whisky_predictions

Hello! 

My name is Andrew Dang and this was my capstone project that was submitted for BrainStation's Data Science diploma. 

The focus of this project was to predict whisky ratings using whisky reviews.

The motivating question I had at the beginning of this project, was ‘What do people talk about when they talk about whisky?” 
As a data scientist, this was a perfect opportunity to apply machine learning techniques to better understand the language that’s used to describe whisky.

I was interested in answering two questions. What words positively influence a whisky’s rating? And furthermore, what flavours positively influence a whisky’s rating?

The dataset used for modeling was scraped from The Whisky Advocate website. The Whisky Advocate is America’s leading spirits magazine, and each review in the dataset was written by an expert. 

There are 5 notebooks uploaded for this project: 
1. Preprocessing and Cleaning
2. EDA and Feature Engineering 
3. Modeling *
4. Findings 
5. Appendix

Addtionally, the 'data' and 'fitted_models' folders contain files required to run these notebooks. A requirements.txt has also been included outlining the modules required for this project. 

* PLEASE NOTE: The Modeling notebook requires trained word embeddings for word2vec and GloVe. They can be downloaded from the following links
* word2vec: https://drive.google.com/file/d/1NtOjkNtbevgg5xWkcop62NYY332tmiJh/view
* GloVe: https://huggingface.co/stanfordnlp/glove/resolve/main/glove.6B.zip
* You may be rquired to copy and paste the GloVe text files into the 'test_data' directory where gensim is installed. You might be able to find that directory through 
* /.../Libe/site-packages/gensim/test/test_data

If you have any troubles accessing any of the files within this folder, please contact me at andrew.dang94@gmail.com.  
