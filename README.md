# COVID-19_dataset

This dataset contains a metadata file (train.json) and a folder (article.zip) of related articles. 


**Description of the JSON metadata format**
- ID: an unique ID of each claim.
- claim: the statement.
- claimant: the speaker of the claim.
- date: when the claim was made.
- label: truth label of the claim.
- source: the fact checking website the claim collected from.
- related_articles: article ids for each related article associated with the claim. 
(Note that this id is served as the text file's names in the article folder)

- country: the country of the claim originated.
- explanation: explanation of the labelling result. 

