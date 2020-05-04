# Email_Ranking_Summarization

#Title:-
Automatic Text Summarization and Ranking of Email Corpus 

#Abstract:-
With the advent of Internet, email communication has become a huge part of the information sharing in the corporate and personal world. The corporate mails continues to rule the world of business. According to the Campaign Monitor source, it is said that an on an average, a working professional receives 120 emails per day. A significant amount of time is spent reading these emails and responding to it. There are emails that are very sensitive that should be handled in a timely manner. This project aims to help the user with the first part using ranking and text summarization. Summarization is a process of obtaining an abridged version of documents so that user can have a quick overview of what the email is about. Emails from the Enron Company are used as a corpus for the system. Information Retrieval features like Term Frequency, Inverse Document Frequency and Cosine Similarity are used for ranking of the emails. A variation of page rank (Text Rank) is used for summarizing the documents based on ranking the sentences in the email. The system can be considered as a base framework for Unsupervised Learning in text summarization

#Packages Used:-
1. numpy == 1.17.4
2. pandas == 0.24.2
3. matplotlib == 3.1.0
4. seaborn == 0.9.0
5. spacy == 2.2.3
6. nltk == 3.4.5
7. scipy == 1.4.1
8. networkx == 2.3
9. jupyterlab == 1.0.2
10. notebook == 6.0.0


#Important info before executing the code:-

1. Two notebooks have been submitted
    
    a) abalas26_project_pre.ipynb:- This is where the data is extracted. The initial dataset was considered which is around 1.0GB 
                                    I have not uploaded the data for this. The processing will also take around 10 minutes to execute on
                                    a normal computer without GPU. 

                                    Instead I have provided the code as well as a PDF of the same, please feel free to look into the code 
                                    and output in the PDF.

                                    If you still wish to run the code, please download the data here: https://www.kaggle.com/wcukierski/enron-email-dataset . Click on Download Data -> Unzip and store the csv file in the same path as the notebook

                                    Please run the entire notebook in a sequence and view the output

    b) To make this simple, after data extraction from the huge file, i have made an intermediate csv file emails_filtered.csv. Which contains the filtered data. This is used in the rest of the project. 

    c) abalas26_project.ipynb: Uses the csv file generated in step (b), Please make sure to have the csv file and this notebook in the same folder.
    Run the notebook in a sequence.


#Instructions to Run the Code:-

1. Make sure Python 3.5+ version is installed in the system

2. Install pip to download all necessary packages

    Command to install pip : a) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
                             b) python3 get-pip.py

3. All the packages needed to execute the programs are placed in the requirements.txt file
    
    Command to install packages: pip install requirements.txt

4. Open Jupyter notebook by executing the below command

    Command to open a Jupyter Notebook: jupyter notebook

5. Naviagte to the folder where the notebooks are placed, two notebooks are submitted, abalas26_project_pre.ipynb and abalas26_project.ipynb

6. Open the Notebook and Click Run All Cells. (If kernel is started and ends abruptly. Please click Restart and Run All). 

    <!-- Please run all the cells in the notebook in the given order, they have dependencies --!>

7. Running the file abalas26_project.ipynb will provide the output at the end of the notebook.
