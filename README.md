# COVMIS

This dataset contains a metadata file (train.json) and a folder (articles.zip) of related articles. 


## Description of the JSON metadata format
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

## Sample Data
```
{
  "claim":" You are 300-900 times more likely to die after getting the COVID-19 vaccine compared to the flu vaccine",
  "claimant":"Alex Berenson; Twitter",
  "date":"2021-02-15",
  "related_articles":[10532,10535,10547,10554,10567,10579],
  "label":0,
  "claim_id":76,
  "country":"United States",
  "source":" Science Feedback",
  "explanation":" Pfizer-BioNTech and Moderna COVID-19 vaccines demonstrated a high level of safety and efficacy during clinical trials in order to receive emergency use authorization from the U.S. Food and Drug Administration. Extensive post-approval monitoring also indicates that the vaccines are safe. Apart from severe allergic reactions (anaphylaxis), the data so far doesn’t indicate that the vaccines cause severe side effects in the general population. The U.S. Vaccine Adverse Events Reporting System (VAERS) is an important tool for monitoring vaccine safety, but VAERS reports alone don’t demonstrate that a vaccine caused the adverse event. Further investigation of reported deaths found no causal link with COVID-19 vaccines."
}
```
## Overview
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

## Ethics
The data is collected from publicly available news outlets. 
The contents of the news only reflect the views of the media and authors, and should be viewed with discretion.

