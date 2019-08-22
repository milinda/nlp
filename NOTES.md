# Word2Vec

## One-hot-encoded representation

**Sample**

```
I like watching a movie.
I enjoy watching a movie.
```

One-hot-encoded vocabulary

```
i        | 1 | 0 | 0 | 0 | 0
like     | 0 | 1 | 0 | 0 | 0
watching | 0 | 0 | 1 | 0 | 0
movie    | 0 | 0 | 0 | 1 | 0
enjoy    | 0 | 0 | 0 | 0 | 1
```

**First sentence**

After stop word removal.

```
[[1,0,0,0,0],[0,1,0,0,0],[0,0,1,0,0],[0,0,0,1,0]]
```

To Read:

* [Word2vec from scratch with Python and NumPy](https://nathanrooy.github.io/posts/2018-03-22/word2vec-from-scratch-with-python-and-numpy/)
* [An intuitive intro of Word2Vec](https://medium.com/towards-artificial-intelligence/an-intuitive-introduction-of-word2vec-by-building-a-word2vec-from-scratch-a1647e1c266c)
* [Word2vec from Scratch with NumPy](https://towardsdatascience.com/word2vec-from-scratch-with-numpy-8786ddd49e72)
* [A Primer on Neural Network Models for Natural Language Processing](http://u.cs.biu.ac.il/~yogo/nnlp.pdf)
* [A Course in Machine Learning](http://ciml.info/)
