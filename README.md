# Boolean Retrieval

Implementing Indexing and Boolean Model

## Processed Dataset
- [English Dataset](https://www.kaggle.com/datasets/ashwanillkagechaad/eng-documents/)
- [Marathi Dataset](https://www.kaggle.com/datasets/ashwanillkagechaad/marathi-documents/)

## Project Overview
This project implements **Boolean Retrieval** by indexing documents and enabling efficient Boolean queries. The process includes:

1. **Preprocessing**
   - Removing unnecessary tags, punctuation, and stopwords
   - Applying stemming using Porter Stemmer

2. **Indexing**
   - Generating **posting lists** for fast retrieval
   - Creating a **positional index** with term frequency (TF) and document frequency (DF)

4. **Boolean Retrieval Model**
   - Implementing AND, OR, and NOT operations for query evaluation
   - Supporting document retrieval based on Boolean expressions

## How to Run
### Prerequisites
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy nltk
```

### Execution
Run the following command to execute the Boolean retrieval system:
```bash
python boolean_retrieval_eng.py
python boolean_retrieval_marathi.py
```

## Example Queries
### AND Query
```python
and_query("calcutta", "telegraph")
and_query("फुलपाखरासारख", "स्वप्नं")
```
### OR Query
```python
or_query("politics", "economy")
or_query("फुलपाखरासारख", "स्वप्नं")
```
### NOT Query
```python
not_query("sports")
not_query("महाराष्ट्र")
```

## Author
**Achal Gawande**  
22075004, achal.gawande.cse22@iitbhu.ac.in

