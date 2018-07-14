# too_big_to_.pkl
Functions, utilizing Klepto, to save in batches objects too large to Pickle and return any number of batches previously saved. 
_____________________________________
  
**Problem:**  
Working in natural language processing (NLP), I rely on large text data that are often too large to pickle without the dreaded memory errors.  

**Solution:**    
I have since created my own functions, one to save and one to return:  
- breaks up lists, dictionaries, and dataframes into specificied number of batches and saves them into files.  
- auto-detects batch files that contain your filename, puts your object back together, and returns your data.  

**Tool:**  
Klepto uses a dictionary interface to batch and archive data into hierarchical files. For more information and installation, please see https://pypi.org/project/klepto/ and https://github.com/mmckerns/tlkklp  
