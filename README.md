#### 🎶 Classification of musical record's genre based on its lyrics.

Have you ever wondered how much lyrics define the musical record's vibe and genre?  
Would you be able to correctly guess record genre just given its lyrics? 

In this repo I am trying to teach ML algorithms to "feel" songs given their lyrics by correctly classifying their genre.

Dataset: over 3 million songs from [Genius song lyrics](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information)   
Genres:   country, pop, rap, rb, rock.  
Approaches:
1. We start with the linear approach: _TF-IDF_ for vectorization; _TruncatedSVD_ for reducing dimensionality and sparsity; _LogisticRegression_ (elastic net) for classification; _RandomizedSearchCV_ for hyper-parameter optimization.  
