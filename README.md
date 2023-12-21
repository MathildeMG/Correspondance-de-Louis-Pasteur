# Louis Pasteur Correspondence

## 1. Description of the Corpus
The corpus for this assignment is composed of twelve letters that Louis Pasteur[^1] sent to his family while he was a student at the Collège de Besançon in France from 1840 to 1842. The twelve letters are specifically from January 1840 to June 1841. They are only the letters sent out by Pasteur, thus this is a corpus of outgoing correspondance which gives a partial insight into the epistolary exchaned Pasteur had with his family. Nonetheless, this gives a very original insight into Pasteurs life, in our case as a student, his worries, his achievments, and all the little daily things that could happen in someones life in the 19th century. 

## 2. Target audience

### ***Historians of Science, Technology and Medicine*** 
For Historians of Science,Technology and Medicine the analysis of such a corpus has multiple utilities. Annotation and Name Entity Recognition can facilitate the identification of certain relationships, scientific collaboratoin for example. It can also give insight into Pasteur's scientific evolution over time. 

### ***Biographers*** 
For Biographers, the correpondance gives insights into more a personal aspects of Pasteur's life such as relationships, worries, challenges etc. The analysis makes it possible to identify key events or relationships and the letters can be contextualized in a broader historical framework. 


### ***Diachronic Linguists*** 
On a linguistic level, analyzing such a corpus is a way to gain insight into language evolution or communication style of Louis Pasteur for example. Furthermore if this corpus were to be studied in a comparativ aspect with another scientist of that time, a historical linguist coul do an analysis of and description of speech community (in this case the 19th century scientific community). Furthermore, cultural and social impact on language evolution for example. 


## 3. Text selection criteria
The texts selected are the first year and a half available in the book "***Correspondance de Pasteur, 1840-1895. 1 / réunie et annotée par Pasteur Vallery-Radot***". Obviously this is not the best way to select a Corpus, I wanted to make it larger by adding all the correspondance for the year 1841 at least but I encountered so many unexpected difficulties that I didn't have the time. The four volumes of the book actually cover the years 1840 to 1895, this is mainly why I decided to work on these texts, they have a lot of potential because the further we go in the years, the more the correspondance is diversified, he corresponds with other scientists and friends etc, which I think could be interesting to investigate. If the corpus was larger and more diversified, Pasteur's hypothetical style difference could be analyzed, when he corresponds with his family and his scientific peers. 

## 4. Collection Process and Processing
The afore mentioned book (the four volumes actually) are available on BnF Gallica which is the gigtal library of the French National Library. The books are freely downloadable and have been OCRized. Different format can be downloaded, PDF, TXT, or JPEG. I have decided to download the PDF version because I had some issue with the TXT format available. Thus, after downloading the PDF version, I have exported said PDF into TXT file using Acrobat Reader. 

Once I had the complete book in txt file, I manually extracted the first twelve letters into separate txt file in order to compose the actual corpus. I did have to check the letters and do soe cleaning and procesing since some words did not come out correctly or were separated in wierd places. 

## 5. Data format and description
### ***Corpus*** 
The corpus is composed of 12 txt files, each containing one letter. The files are named by the date mentioned by Louis Pasteur on the letters themselves: Year - Month - Day. 

### ***Metadata*** 
I have created a csv file containing metadata for the corpus. The LetterID corresponds to the txt file name, SenTo indicates to whom Louis Pasteur has sent the letter. In the case of our corpus he only sent letters to his parents but as mentioned befor, if the corpus was larger, we would have other people in this column. The date refers again to the dates mentioned in the letters. 


| LetterID    | SentTo | Date |
| ---------- | --------- | ---------- | 
| 1840_01_26| Parents| 26 janvier 1840  | 
| 1840_06_08  |  Parents  | 08 juin 1840  | 





[^1]: Louis Pasteur was a French chimist and microbiologist who was born in 1822 and died in 1895. He is considered of one of teh founders of medical microbiology but he was also a chemist. You might have heard his name in the contexte of "pasteurization" which is a process that gets rid of bad microorganisms in food and beverage. Louis Pasteur also developped the vaccines agains anthrax and rabies. See: https://www.britannica.com/biography/Louis-Pasteur.
