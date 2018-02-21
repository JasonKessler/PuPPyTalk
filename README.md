# PuPPyTalkSemioticSquares
Feb. 21, 2018 PuPPY talk on Lexicon Mining and Semiotic Squares

Please see [Talk.pptx](Talk.pptx) for some introductory slides, and a breif survey of psychological literature on the importance of function words in lexicon mining.

The two notebooks used are written in Python 3.6.  Please run

$ pip install scattertext spacy gensim

before using them.  

The first notebook, [Class-Association-Scores.ipynb](nbviewer.jupyter.org/github/JasonKessler/PuPPyTalk/blob/master/notebooks/Class-Association-Scores.ipynb), demonstrates a how to use Scattertext to visualize term-category assocations.  The notebook will motivate and introduce the "Fightin' Words" formula-- the Log-Odds-Ratio with an Informative Dirichlet Prior (Monroe et al. 2008).  Data will be used from Pang et al., 2002.

The second notebook, [Explore-Headlines.ipynb](nbviewer.jupyter.org/github/JasonKessler/PuPPyTalk/blob/master/notebooks/Explore-Headlines.ipynb), shows how to use Scattertext to visualize the interactions between a number of document categories.  The example used will be headlines posted to Facebook accounts from a variety of publishers in 2016. The data is taken verbatim from Max Woolfe's data set, available at https://github.com/minimaxir/clickbait-cluster under the MIT license.

# References
* Cindy K. Chung and James W. Pennebaker. 2012. Counting Little Words in Big Data: The Psychology of Communities, Culture, and History. EASP.
* Susan C. Herring, Anna Martinson. 2004. Assessing Gender Authenticity in Computer-Mediated Language Use: Evidence From an Identity Game. Journal of Language and Social Psychology. 
* Dan Jurafsky, Victor Chahuneau, Bryan Routledge, and Noah Smith. Narrative framing of consumer sentiment in online restaurant reviews. First Monday. 2014.
* Jason S. Kessler. 2017. Scattertext: a Browser-Based Tool for Visualizing how Corpora Differ. ACL System Demonstrations. 
* McInnes, L, Healy, J, UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction, ArXiv e-prints 1802.03426, 2018.
* Burt L. Monroe, Michael P. Colaresi, and Kevin M. Quinn. 2008. Fightin’ words: Lexical feature selection and evaluation for identifying the content of political conflict. Political Analysis.
* Newman, ML; Groom, CJ; Handelman LD, Pennebaker, JW. Gender Differences in Language Use: An Analysis of 14,000 Text Samples. 2008.
* Bo Pang, Lillian Lee, and Shivakumar Vaithyanathan. 2002. Thumbs up? Sentiment Classification using Machine Learning Techniques, EMNLP.
* James W. Pennebaker, Carla J. Groom, Daniel Loew, James M. Dabbs.  2004. Testosterone as a Social Inhibitor: Two Case Studies of the Effect of Testosterone Treatment on Language. J Abnorm Psychol.

