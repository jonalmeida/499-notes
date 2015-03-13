A boolean based question answering system
=========================================

> Presenter: Jiayi Wu
>
> Date: 23/01/2015
>
> Time: 12:00 pm

# Summary:

This seminar is about using a boolean question answering system to retrieve more valuable and precise information from search results. Using a dataset of information retrieved from the Google Search API, natural language is used to send a query to the API, in order to retrieve an index of documents to be analyzed. Each document listed, is retrieved and scraped of all text information. The document is then processed using Porter Stemming to remove English tense information and then indexed. The questions are then analyzed against the newly indexed documents in-order to retrieve the answer to the question.

# Questions:

 1. What information is actually sent to the Google Search API in order to get a meaningful dataset?

 2. This sounds very similar to implementing the Cosine Similarity Measure, but there wasn't any mention of it. Does this system implement it or is it influenced by it?
