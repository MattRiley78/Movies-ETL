# Movies-ETL
## Project Overview
Amazing Prime is sponsoring a hackathon for their streaming service.  They are looking to create a clean dataset of movies and user rankings to help predict popular movies.  The ultimate goal is to find lower budget movies that have not yet been purchased for streaming services and buy exclusive rights to those movies.  Over the past week, our team has been perfecting the code to Extract the different data sources, Transform them into usable data, and Load them into a SQL database.  The bulk of this process is performed using Python in Jupyter Notebook.

The Purpose of this project to:
1. Make sure the ETL processes are working correctly.
2. Combine all these processes into a single function that can be used with future datasets.

## Results

Four different deliverables were created in order to achieve the final result:

1. The consolidation of the week's work that includes code that will read the data files and create three separate DataFrames

    ### Wikipedia Movie Info Dataframe


    ### Kaggle Metadata DataFrame


    ### MovieLens Ratings DataFrame
    


2. Extraction and Transformation of Wikipedia so it can be merged with Kaggle Metadata.

    ### Confirmation of Wikipedia Movie Info Dataframe


    ### Column LIst of Wikipedia Movie Info Dataframe


3. Extraction and Transformation of Kaggle and MovieLens data and merging of all Dataframes.

    ### Movies With Ratings and Movies Dataframes

4. Final creation of movie database as a function to load as tables into SQL.

    ### Confirmation of Movie Table Load

    
    ### Confirmation of Ratings Table Load