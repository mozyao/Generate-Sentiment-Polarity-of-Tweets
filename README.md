
CMPT413 Term Project 

Files list:
1) tweet_extractor.py
    the extractor that generating data from twitter using its API. feel free to  modify the tracklist =[ 'q1','q2',...] of your query in line 28.
2) D2.txt
    Data file generated from tweet_extractor.py , was used to be our inpupt data.
    We abondoned it due to quantity and lack of accurate labels['Pos','Neg']
    
3) df.csv
    Current dataset can be obtained from https://docs.google.com/file/d/0B04GJPshIjmPRnZManQwWEdTZjg/edit
    
4) project.ipynb
    the main notebook showing all the works we done 
    
5) Out put files - output.readme which has the link of google drive files I uploaded.
models.zip: include all models:
    KERAS_MODEL = "model.h5"
    WORD2VEC_MODEL = "model.w2v"
    TOKENIZER_MODEL = "tokenizer.pkl"
    ENCODER_MODEL = "encoder.pkl"
figures.zip: all figures

6) next.ipnb 
    experiment of GloVe
    
7) pre_work_with_abandon_data.ipynb
    previous work before we changed the data and goal , just for record. 
    Not necessary to take a look

Evaluation:
All the evaluation work was done inside the project.ipynb


Output:
All useful plots and tabels has been save as png files together with all ouputed models in the output.zip


Work Division:
Please check username.readme

Notice:
Due to the  issue of inaction of member Nicholas, Porject Goal Shifted:(  as we only accomplished phase I.
Details included inside  presentation check cmpt413_project.key
Youtube Link:    https://youtu.be/T3CPWKEvFlc






Pre-installed Packages:
You can use commands below to install corressponding  packages inside noteboook
if before you run my notebook if necessary.
!pip install gensim --upgrade
!pip install keras --upgrade
!pip install pandas --upgrade
!pip install tensorflow
!pip install wordcloud
nltk.download('stopwords')


