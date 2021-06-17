# COVMIS

This dataset contains a metadata file (train.json) and a folder (articles.zip) of related articles. 


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

**Overview**
- The data folder contain the whole dataset, there are 14,384 claims and 134,321 articles.
- The foreign_language_articles folder contains articles in 24 different languages other than English:

| Language | Number of Articles |
| --- | --- |
| Spanish, Castilian | 10140 |
| Portuguese | 2954 |
| Macedonian | 1939 |
| French | 1931 |
| Italian | 1455 |
| German | 905 |
| Ukranian | 808 |
| Croatian, Valencian | 522 |
| Hindi | 487 |
| Indonesian | 411 |
| Japanese | 305 |
| Korean | 289 |
| Russian | 286 |
| Catalan | 251 |
| Greek | 195 |
| Romanian | 167 |
| Estonian | 159 |
| Polish | 155 |
| Chinese | 143 |
| Dutch, Flemish | 139 |
| Latvian | 119 |
| Bengali | 113 |
| Marathi | 113 |
| Arabic | 126 |

**Ethics**

The data is collected from publicly available news outlets. 
The contents of the news only reflect the views of the media and authors, and should be viewed with discretion.

