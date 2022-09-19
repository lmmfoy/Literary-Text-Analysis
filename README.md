# Work for McGill's "LLCU 612: Literary Text Mining" graduate seminar
Using Python, Matplotlib, HTML, CSS, Regular Expressions
Libraries: Natural Language Toolkit (NLTK), NumPy, Beautiful Soup, urllib.request, scikit,
Text editor: Atom
Environments used: Voyant Tools, Juypter Notebooks, ObservableHQ.

    compile and prepare for analysis a variety of types of digital texts
    use text analysis and statistical software to study digital texts
    produce visualizations from analytic and statistical data
    think algorithmically about digital texts
    navigate between close and distant reading practices
    describe and demonstrate the value and limitations of digital methodologies
    have some expertise and experience in learning new technical skills, especially using web resources

Compiling a corpus
Web scraping
Pre-processing a corpus (cleaning, format conversion, etc.) 
    Text processing, tokenization, determining word frequency, using stoplists
    Distribution of terms, building concordances, analyzing collocates and correlations
    Visualization using graphs, word clouds, lexical dispersion plots, etc.
    Document similarity, identification of authors based on use of language
    Normalization of terms using stemming, lemmatization 
    Transforming and mapping words in a text -  Search and count words with lexical transformations (i.e. case changes, stemming, lemmatization), word sense lookups with WordNet, resursive searching for hyponyms (words with more specific meanings) from synset returned using WordNet - tagging parts of speech using NLTK - 
Examining Frequencies and Distribution for a Specific Part of Speech - concept of part-of-speech tagging as an additional way of processing texts. 

    Ngrams/repeating text
    
  A common task when working with a larger corpus is to try to determine how documents relate to one another – how similar or different they are, or how they might cluster together - using sentence length, document term matrix, TF-IDF scores/values - term frequency * inverse document frequency - cosine similarity - visualizing document clusters with multidimensional scaling & dendrograms
    
    topic modelling
    sentiment analysis based on training sets, word lists, and WordNet
    parts-of-speech
    named entity recognition
    semantic analysis
    
    distribution/collocates/correlations/stoplists

## Main project: Text Mining Female Masculinity in Sixteenth and Seventeenth-Century Britain
See **Text Mining Female Masculinity in Early Modern Britain.ipynb**, and associated appendixes: **Appendix A - Corpus Summary & Ordering the Corpus.ipynb** and **Appendix B - Corpus Normalization.ipynb**. 

I explored gender fluidity in sixteenth and seventeenth-century Britain using a corpus of just over 1000 texts from the period. I created this corpus using 25,368 texts from Early English Books Online (EEBO), Eighteenth Century Collections Online (ECCO), and Evans Early American Imprints, and filtered them using key words/phrases and dates. I organized and cleaned these texts, and standardized spelling as much as possible. I then created dictionaries of concordances (a method of exploring the context of key words and phrases, by showing the words and the passages around them), and graphed collocates (words that appear in proximity to the specified key word or phrase). I went on to perform sentiment analysis on the texts to gain some insight into whether references to my key words/phrases were negative or positive, and tracked how this sentiment changed over time.
