# NLP-Project

Begin()
    •	Tokenize and extract sentences from the document to be summarized.
    •	Decide on the number of sentences, k, that we want in the final summary
    •	Build a document-term feature matrix using weights like TF-IDF or Bag of Words.
    •	Compute a document similarity matrix by multiplying the matrix by its transpose.
    •	Use these documents (sentences in our case) as the vertices and the similarities between each pair of documents as the weight or score coefficient we talked about       earlier and feed them to the PageRank algorithm.
    •	Get the score for each sentence.
    •	Rank the sentences based on score and return the top k sentences.
End()

# Architecture Design
![image](https://user-images.githubusercontent.com/68732493/201905563-85d0916c-7684-4dbf-a898-37e174b66b26.png)

# Flow Chart

![image](https://user-images.githubusercontent.com/68732493/201905694-ce98620e-da37-4b41-9886-1e368ee01a34.png)

