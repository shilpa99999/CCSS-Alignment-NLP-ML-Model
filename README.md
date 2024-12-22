# CCSS-Alignment-NLP-ML-Model
CCSS Alignment NLP/ML Model

Data set:

CSV file with about 1,500 rows 

Important Columns​

CCSS id:  e.g., CCSS.ELA-LITERACY.L.K.1​

Description: e.g., Demonstrate command of the conventions of standard English grammar and usage when writing or speaking

Task:

Using NLP and ML to build a model​

Input: any texts and a number N​

Output: the closest N number of CCSS ids to the input texts ranked by the closeness

Brief overview of Testing and evaluation

Testing the Model with Various Inputs:-

This step is crucial for understanding how well the model performs on different types of input data. Here are the steps involved:

Test Texts: A list of sentences is defined, each representing a different type of educational standard that might be in the dataset.
Finding Closest CCSS IDs: For each test text, the find_closest_ccss_ids function is called to find the most similar Common Core State Standards (CCSS) descriptions in the dataset.
Evaluation is based on the model's ability to return relevant and accurate descriptions for each test input.
Manual Inspection: The results for each input text are printed and manually inspected to assess the relevance and accuracy of the returned descriptions.

SUMMARY:-

The testing and evaluation process involves using a set of predefined test inputs to assess the model's ability to return relevant, accurate, and diverse descriptions. Manual inspection of the outputs helps in evaluating the model's performance and identifying areas for improvement. This process ensures that the model can reliably find and recommend educational standards based on input queries.
