# PuPPyTalkSemioticSquares
Feb. 21, 2018 PuPPY talk on Lexicon Mining and Semiotic Squares

Please see [Talk.pptx](Talk.pptx) for some introductory slides, and a breif survey of psychological literature on the importance of function words in lexicon mining.

The two notebooks used are written in Python 3.6.  Please run

$ pip install scattertext spacy gensim

before using them.  

The first notebook, [Class-Association-Scores.ipynb](nbviewer.jupyter.org/github/JasonKessler/PuPPyTalk/blob/master/notebooks/Class-Association-Scores.ipynb), demonstrates a how to use Scattertext to visualize term-category assocations.  The notebook will motivate and introduce the "Fightin' Words" formula-- the Log-Odds-Ratio with an Informative Dirichlet Prior (Monroe et al. 2008).  Data will be used from Pang et al., 2002.


# References
* Burt L. Monroe, Michael P. Colaresi, and Kevin M. Quinn. 2008. Fightin’ words: Lexical feature selection and evaluation for identifying the content of political conflict. Political Analysis.
* Bo Pang, Lillian Lee, and Shivakumar Vaithyanathan. 2002. Thumbs up? Sentiment Classification using Machine Learning Techniques, EMNLP.
