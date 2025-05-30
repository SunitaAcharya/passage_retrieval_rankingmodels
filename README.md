# Evaluation of Passage Retrieval on Ranking models

 $${\color{blue}A \space dissertation \space presented \space in \space part \space fulfilment \space of \space the \space requirements \space of \space the \space Degree \space of \space Master \space of \space Science \space at \space The \space University \space of \space Glasgow}$$

 Summary

The project focus on passage retrieval from relevant documents with the goal of implementing different ranking models and retrieval approaches. All the models and approaches experiment on three corpus, Vaswani dataset, Cranfield dataset, Beir CQADupStack webmasters dataset. All the documents run under Py-terrier framework where several pre-defined functions are used to obtain steps like document indexing, retrieval, and relevant documents from the document collection are implemented first to experiment on high-ranked relevant passages. The tasks focus on the implementation of different combinations of traditional models and neural models with end-to-end retrieval and top-10 reranking retrieval approaches are used on datasets during evaluation. The results show that neural ranking models significantly outperformed traditional ranking models and re-ranking retrieval approaches perform higher than end-to-end retrieval across the datasets. Significance testing is used to test effectiveness which gives interesting results, Cranfield and Beir CQADupStack webmasters show that neural ranking with end-to-end retrieval improves performance however, in the Vaswanidataset, it is either a decrease in performance or not significant at all. Possible explanations for this evaluation are elaborated with relevant outputs discussed in this report.


Result

In answer to all the research questions mentioned in the literature review, it is observed that in all three datasets, overall figures state that the neural ranking model (ColBERT) with re-ranking retrieval outperforms traditional ranking models. While comparing the traditional model BM25 as a baseline with neural models shows it improves the significant performance of the neural ranking model ColBERT with end-to-end retrieval and re-ranking retrieval in all three datasets. However, comparing the neural model ColBERT as a baseline with traditional models shows different results in all three datasets. It shows that the significance performance is improved in the traditional end-to-end retrieval model on the Vaswani dataset, neural model (ColBERT) as re-ranked retrieval on the Cranfield dataset, and no improved performance at all in Beir-webmasters dataset. Hence, BM25 is the best model to improve the performance of the neural model whereas ColBERT model is not the best model to improve the performance of the traditional model.


