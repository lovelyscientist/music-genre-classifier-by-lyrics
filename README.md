#### Classification of musical records into genres based on its lyrics 🎶.

Have you ever wondered how much song lyrics define the song vibe and genre?  
Would you be able to correctly guess song genre just given its lyrics?  
In this repo I am trying to teach ML algorithms to "feel" songs given their lyrics by correctly classifying their genre.

Dataset: over 3 million songs from [Genius song lyrics](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information)   
Genres:   country, pop, rap, rb, rock.  
Approaches:
1. We start with the linear approach: TF-IDF for vectorization; TruncatedSVD for reducing dimensionality and sparsity; LogisticRegression (elastic net) for classification; RandomizedSearchCV for hyper-parameter optimization.  
