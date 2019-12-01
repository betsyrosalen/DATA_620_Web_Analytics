# Potential Data Sources

Source: <https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0>

## Recipe ingredients.	

For their 2011 paper, “Flavor network and the principles of food pairing,” four scientists analyzed 56,498 recipes downloaded from three websites — allrecipes.com, epicurious.com, and menupan.com. To support their findings, the authors published two datasets. One names the cuisine and ingredients for each recipe. The other dataset counts how often any two ingredients appeared in the same recipe. (Parmesan cheese and beef appeared together 93 times; starfruit and Algerian geranium oil just once.) Related: “food2vec – Augmented cooking with machine intelligence,” published last month. [h/t Rob Barry]

<http://www.nature.com/articles/srep00196>  
<http://www.nature.com/articles/srep00196#supplementary-information>  
<https://jaan.io/food2vec-augmented-cooking-machine-intelligence>  

#### _Data easily downloaded in CSV format._

## Words kids learn.	

Wordbank is an “open database of children's vocabulary development.” So far, the Stanford-hosted project has gathered data from more than 71,000 standardized and anonymized vocabulary questionnaires across 23 languages. You could spend hours exploring the data online, charting how quickly children learn individual words, how quickly the same word (e.g., “grandma,” “abuela,” “ба́бушка”) is learned in different languages, and connections between words. You can download the data for each word or for each child’s vocabulary. Bonus: Wordbank has an R package and a GitHub repository. [h/t Hacker News user "Jasamba"]

<http://wordbank.stanford.edu/>  
<http://wordbank.stanford.edu/analyses?name=item_trajectories>  
<http://wordbank.stanford.edu/analyses?name=uni_lemmas>  
<http://wordbank.stanford.edu/analyses?name=networks>  
<http://wordbank.stanford.edu/analyses?name=item_data>  
<http://wordbank.stanford.edu/analyses?name=instrument_data>  
<http://langcog.github.io/wordbankr/>  
<https://github.com/langcog/wordbank>  

#### _This one may be harder to access in Python.  There is an R package to access data but I don't see any other way of accessing it._

## Trump, McConnell, Schumer, Ryan, and Pelosi on TV.

The Internet Archive has pumped footage from CNN, Fox News, MSNBC, and the BBC through software trained to recognize the faces of Donald Trump and majority/minority leaders of the U.S. House and Senate. The result: Face-O-Matic, a dataset released to the public last week. For each face the software found, the dataset includes the network, program, date, time, duration, and a link to the footage on the TV News Archive. Since mid-July, Face-O-Matic has logged more than 50,000 sightings. [h/t Nancy Watzman]

<https://archive.org/details/faceomatic>  
<http://blog.archive.org/2017/09/06/face-o-matic-data-show-trump-dominates/>  
<https://archive.org/details/tv>  

#### _Data easily downloaded in csv format._

## Chyrons.	

The TV News Archive’s new “Third Eye” project is extracting chyrons — those placards of text at the bottom of news broadcasts, also known as “lower thirds” — from four major cable networks: BBC News, CNN, Fox News, and MSNBC. The resulting database contains every chyron that Third Eye’s optical character recognition (OCR) software has extracted since late August. Related: This Washington Post piece analyzing cable news’ chyrons during James Comey’s congressional testimony, and this explanation of how they did it. [h/t Nancy Watzman]	

<http://blog.archive.org/2017/09/21/tv-news-chyron-data/>  
<https://archive.org/services/third-eye.php>  
<https://www.washingtonpost.com/graphics/2017/politics/comey-hearing-chyrons/>  
<https://source.opennews.org/articles/how-we-tracked-cable-news-chyrons/>  

#### _Data can be downloaded in tsv format from here: <https://archive.org/download/third-eye>_

## Pan-African surveys.	

Afrobarometer “is a pan-African, non-partisan research network that conducts public attitude surveys on democracy, governance, economic conditions, and related issues in more than 35 countries in Africa.” You can download data from the first six rounds of surveys, conducted between 1999 and 2015. You can also read the detailed questionnaires and explore the results online. Note: To download the data, you’ll need to create a (free) account on the website. [h/t Jeffrey Arnold]	

<http://www.afrobarometer.org/about>  
<http://www.afrobarometer.org/data/merged-data>  
<http://www.afrobarometer.org/surveys-and-methods/questionnaires>  
<http://afrobarometer.org/online-data-analysis/getting-started>  

#### _Data in .sav format.  May be able to import with python...?_

> ##### you need pandas >= 0.25.0 for this
> 
> ```
> import pandas as pd
> df = pd.read_spss('your_spss_file.sav')
> ```
> 
> This has library pyreadstat as a requirement, so you might have to install that first:
> 
> ```
> pip install pyreadstat
> ```
 
Source: <https://stackoverflow.com/questions/14647006/is-there-a-python-module-to-open-spss-files>

## 34,361 European migration deaths.

The Amsterdam-based activist group UNITED for Intercultural Action has, since the early 1990s, been collecting information about the deaths of Europe’s refugee-seekers. The organization's volunteers “update the data annually, spending six months at a time verifying reports, categorising deaths and entering them into the database,” according to The Guardian's story about the endeavor and its findings. “When the project began, they received physical clippings from a network of groups around Europe. Now, the data is collected from email submissions and Google Alerts in a number of languages.” The story features a PDF-listing of the deaths, including the date the migrants were found dead, names and countries of origin (where known), and the causes of death. The Italian civic-data organization OnData has converted the PDF to a spreadsheet. [h/t Giuseppe Sollazzo]

<http://www.unitedagainstracism.org/>  
<https://www.theguardian.com/world/2018/jun/20/the-list-europe-migrant-bodycount>  
<http://ondata.it/>  
<https://github.com/ondata/the-list>  

#### _Data easily downloaded in CSV format from here: <https://github.com/ondata/the-list/blob/master/data/refugeesAndMigrants.csv>_  
#### _and here: <https://github.com/ondata/the-list/blob/master/data/sources.csv>_

## Freedom lawsuits in early America.	
O Say Can You See, a project partially funded by the National Endowment of the Humanities, “documents the challenge to slavery and the quest for freedom in early Washington, D.C., by collecting, digitizing, making accessible, and analyzing freedom suits filed between 1800 and 1862, as well as tracing the multigenerational family networks they reveal.” The project provides several ways to access the data and documents; it covers more than 500 lawsuits, nearly 5,000 people, and tens of thousands of relationships. You can also explore the cases, people, and families online. [h/t Jan Willem Tulp]

<http://earlywashingtondc.org/>  
<http://earlywashingtondc.org/about/data>  
<http://earlywashingtondc.org/about>  
<http://earlywashingtondc.org/cases>  
<http://earlywashingtondc.org/people>  
<http://earlywashingtondc.org/families>  

#### _See 'Getting Started with RDF' at this page: <http://earlywashingtondc.org/about/data> for details about how to get data...  This one may be a bit more complicated than some of the others, but not too bad I think..._

## Drama.	

The Drama Corpora Project has collected and processed more than 800 plays in German, Greek, Spanish, Russian, Latin, and English. For each play, the project provides a structured-data version of the text, a network diagram, speech distribution metrics, plus several other files and features. [h/t Lynn Cherny]	

<https://dracor.org/>  
<https://en.wikipedia.org/wiki/Text_Encoding_Initiative>

#### _Data in various formats, easy to download.  Can do text and network analysis.  Maybe not the most exciting topic though?_

## One million comic book panels.	
Comic books make use of white space — or gutters — to propel the story forward, relying on readers’ intuitive ability to fill in the gaps between panels. To see whether computers could learn to make the same inferences, a group of computer scientists built a giant corpus of public-domain comics and tried training a series of neural networks on it. (Spoiler: Humans are much better at this.) The underlying dataset contains 1.2 million panels from nearly 200,000 scanned pages of nearly 4,000 books in the Digital Comic Museum, all published during the 1938–1954 “Golden Age” of American comics. It also contains 2.5 million chunks of text extracted from the comics’ speech balloons, thought bubbles, and narration boxes. [h/t Robin Sloan]	

<https://arxiv.org/abs/1611.05118>  
<https://obj.umiacs.umd.edu/comics/index.html>  
<https://digitalcomicmuseum.com/>  

#### _Very large downloads.  Probably not the best choice for this project._