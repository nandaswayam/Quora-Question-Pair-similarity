# Quora-Question-Pair-similarity
Predict whether a given pair of Quora questions are identical or not

Data Source:- 
https://www.kaggle.com/quora/question-pairs-dataset

<h2>Context</h2>
Quora's first public dataset is related to the problem of identifying duplicate questions. At Quora, an important product principle is that there should be a single question page for each logically distinct question. 
For example, the queries “What is the most populous state in the USA?” and “Which state in the United States has the most people?” should not exist separately on Quora because the intent behind both is identical. Having a canonical page for each logically distinct query makes knowledge-sharing more efficient in many ways: for example, knowledge seekers can access all the answers to a question in a single location, and writers can reach a larger readership than if that audience was divided amongst several pages.The dataset is based on actual data from Quora and will give anyone the opportunity to train and test models of semantic equivalence.

<h2>Content</h2>
There are over 400,000 lines of potential question duplicate pairs. Each line contains IDs for each question in the pair, the full text for each question, and a binary value that indicates whether the line truly contains a duplicate pair.

The task is to classify pairs of Quora questions as being duplicates or not.
