# KG_based_QA_System
Knowledge Graph Construction with BERT and Graph Convolutions for Data Privacy

1. Requested html wiki pages using requests library in Python and Parsed wiki pages using beautiful soup
2. Collected URLs from See Also and Categories section on Wikipedia as well as extracted context and references from Wikipedia and post-processed them to get more relevant information
3. Completed data mining from wiki_infobox and Google PAA(People also ask) when querying the core questions about data privacy 
4. Applied Google Named Entity Recognition (NER) service to data mining results generate entities to build the KG.
5. Performed sentence embedding using BERT Transformer for Question&Answering(QA) on the KG. 
6. Utilized a graph convolution approach for improving QA results
