Intelligent Search Using Semantic and KNN

Hosted application on Hugging Face to use: https://huggingface.co/spaces/kkr5155/Intelligent-search-using-semantic-and-KNN

Folder Structure

|-Data
	|-brand_category.csv
	|-categories.csv
	|-offer_retailer.csv
|-Fetch.ipynb
|-unified_test.csv
|-readme.md
|-requirements.txt
|-unified.csv


Introduction
This tool enables intelligent search using semantic and K-nearest neighbors (KNN) techniques. It empowers users to find similar items within a dataset based on semantic understanding.

Getting Started
Follow these simple steps to run the tool locally:

Prerequisites

You can install these dependencies using the requirements.txt file provided.

Run the "Fetch.ipynb" notebook to perform data scraping, data preprocessing, and text data preprocessing. This step prepares the data for semantic search.

Semantic Search
Choose one of the following semantic search methods based on your preference:

a. Basic Semantic Search
Run the code under "Basic Semantic Search" to find similar offers based on semantic understanding.
Customize the input query to find relevant results.

b. Semantic Search with Context Recognition
Use the code under "Semantic Search with Context Recognition" for more context-specific results.

The tool will identify the type of input text (e.g., retailer, brand, or product category) and provide tailored searches.

Running the Tool
After preparing your data and selecting the semantic search method, you can execute the code to run the tool locally.

Conclusion
This tool enhances data exploration and search capabilities, allowing you to find similar items within your dataset based on semantic understanding. Whether you need a basic semantic search or context-specific results, this tool provides valuable insights and tools for efficient data analysis.