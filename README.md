# Louis Pasteur Correspondence
![800px-Albert_Edelfelt_-_Louis_Pasteur_-_1885](https://github.com/MathildeMG/Louis-Pasteur_CD_A4/assets/150797037/912a3388-54b7-415c-bc3b-704dea7f01f3)

## 1. Description of the Corpus
The corpus for this assignment is composed of twelve letters that Louis Pasteur[^1] sent to his family while he was a student at the Collège de Besançon in France from 1840 to 1842. The twelve letters are specifically from January 1840 to June 1841. They are only the letters sent out by Pasteur, thus this is a corpus of outgoing correspondance which gives a partial insight into the epistolary exchaned Pasteur had with his family. Nonetheless, this gives a very original insight into Pasteurs life, in our case as a student, his worries, his achievments, and all the little daily things that could happen in someones life in the 19th century. 

## 2. Target audience

### ***Historians of Science, Technology and Medicine*** 
For Historians of Science,Technology and Medicine the analysis of such a corpus has multiple utilities. Annotation and Name Entity Recognition can facilitate the identification of certain relationships, scientific collaboratoin for example. It can also give insight into Pasteur's scientific evolution over time. 

### ***Biographers*** 
For Biographers, the correpondance gives insights into more a personal aspects of Pasteur's life such as relationships, worries, challenges etc. The analysis makes it possible to identify key events or relationships and the letters can be contextualized in a broader historical framework. 


### ***Diachronic Linguists*** 
On a linguistic level, analyzing such a corpus is a way to gain insight into language evolution or communication style of Louis Pasteur for example. Furthermore if this corpus were to be studied in a comparativ aspect with another scientist of that time, a historical linguist could do an analysis of- and description of- speech community (in this case the 19th century scientific community). Furthermore, cultural and social evolution and its impact on language can be explored for example. 


## 3. Text selection criteria
The texts selected are the first year and a half available in the book "***Correspondance de Pasteur, 1840-1895. 1 / réunie et annotée par Pasteur Vallery-Radot***"[^2]. The four volumes of the book actually cover the years 1840 to 1895, this is mainly why I decided to work on these texts, they have a lot of potential because the further we go in the years, the more the correspondance is diversified. Pasteur corresponds with other scientists and friends, family, lover etc, which could be interesting to investigate. With a larger and more diversified corpus, one could get a very interesting overview of Pasteur's life and his manner of communcating with different people. 

## 4. Collection Process and Processing
The afore mentioned book (the four volumes actually) are available on BnF Gallica which is the digtal library of the French National Library. The books are freely downloadable and have been OCRized. Different format can be downloaded, PDF, TXT, or JPEG. I have decided to download the PDF version and export them into TXT file using Acrobat Reader. 

Once I had the complete book in TXT file, I manually extracted the first twelve letters into separate TXT files in order to compose the actual corpus. I did have to check the letters and do some cleaning and procesing since some words did not come out correctly due to special characters or were separated in wierd places. 

## 5. Data format and description
### ***Corpus*** 
The corpus is composed of 12 TXT files, each containing one letter. The files are named by the date mentioned by Louis Pasteur on the letters themselves: Year - Month - Day. 

### ***Metadata*** 
I have created a CSV file containing metadata for the corpus. The LetterID corresponds to the TXT file name (the date), SenTo indicates to whom Louis Pasteur has sent the letter. In the case of our corpus he only sent letters to his parents but as mentioned before, if the corpus was larger, we would have other people in this column. The date refers again to the dates mentioned in the letters. 


| LetterID    | SentTo | Date |
| ---------- | --------- | ---------- | 
| 1840_01_26| Parents| 26 janvier 1840  | 
| 1840_06_08  |  Parents  | 08 juin 1840  | 

### ***SpaCy output*** 
The SpaCy output is also a csv file containing the processed and annotated letters. 
The first three field correspond to the metadata, then there is a column for the unprocessed texts then there are the tokenized texts (segmentated strings into individual words). The Lemmas is the identification of the root of each words. The part of speech column refers to the POS-tagging and the Proper Nouns are the actual words from the letters that correspond to the POS tagging. The same goes for the two last columns but applied to Name Entity Recognition; the second to last one contains the tags, whereas the last one contains the actual words that refer to them. 

| Filname    | SentTo    | Date       | Text      |Tokens     |Lemmas|Part of speech|Proper Nouns|Named Entities|NE Words|
| ---------- | --------- | ---------- | ----------|----------|----------|----------|----------|----------|----------|




[^1]: Louis Pasteur was a French chimist and microbiologist who was born in 1822 and died in 1895. He is considered of one of teh founders of medical microbiology but he was also a chemist. You might have heard his name in the contexte of "pasteurization" which is a process that gets rid of bad microorganisms in food and beverage. Louis Pasteur also developped the vaccines agains anthrax and rabies. See: https://www.britannica.com/biography/Louis-Pasteur.

[^2]: See: https://gallica.bnf.fr/ark:/12148/bpt6k6473241n/f1.item
