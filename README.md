 Sindhi Unicode-8 based repository is developed in CSV format. 
All the Sindhi tokens available in repository are tagged with Universal Part of Speech (UPOS) and Sindhi Part of Speech (SPOS).
Repository is developed on basis of results of Sindhi online natural languages processing(NLP) tool (http://www.sindhinlp.com) for parsing, tagging, morphological and sentiment analysis, stemming and lemmatization of Sindhi text.
Sindhi corpus documents are processed for annotation in Sindhi NLP tool separately. 
The results of annotation are accumulated to develop data repository.
Repository is valuable to comprehend the grammatical, sentimental, syntactic and morphological structure of Sindhi text.
Repository is signiﬁcant source for machine learning and NLP analysis for information retrieving, language modelling, universal dependency, machine translations, sentiment analysis and computational linguistics operations
Annotation process is done on basis of identification of each Sindhi token. 
Tagger read the Sindhi text first, then convert it from left side to right side as Sindhi text is right hand written text. It split the text into independent tokens to tag each token with UPOS and SPOS.
Tagger identify the status of Sindhi token from data dictionary and tag it with UPOS and SPOS accordingly.
There is matching between UPOS and SPOS with little difference in UPOS tag PART and SPOS tag adverb.
Sindhi adverb is used to tag all the Sindhi token using all the properties of adverb therefore, it is used to Sindhi words no, not, never as well however, UPOS tag PART is used to tag the words no, not, never. Therefore, Sindhi tagger uses UPOS tag PART while tagging Sindhi words no, not, no one never and other such types of the word.
Sindhi tagger uses post position for possessive markers whereas, UPOS uses PART tag for possessive markers.
Tagger performs the annotation analysis process to show the usage of each tag.
The analyzer shows the number of tokens and execution time which taken by processor.
Tagger analyze the sentence or corpus to identify the morphological words. It shows the morphological words separately according to morphological forms. The simple and bound forms of morphology are used however, bound form is divided into complex, compound and reduplicated forms. 
