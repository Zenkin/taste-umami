[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zenkin/taste-umami/blob/main/predict_umami_taste.ipynb)

# Intelligent big data analytics technologies for creating a guide to functional food ingredients

There are about 10,000 taste buds on our tongue, but we still don't know exactly how we recognize taste. Moreover, it is often difficult to understand what the taste itself is.

![fishy](https://github.com/Zenkin/taste-umami/blob/main/figs/taste.png?raw=true)

Determination of umami flavor intensity is an important task in order to improve product quality, for example, replacing chemically synthesized additives with additives of natural origin. To solve this problem, a cascade algorithm based on CatBoost and BERT was developed. The functionality of the algorithm can be found at the following [link](https://taste.infochemistry.ru).

The working principle of the algorithm is shown in the figure below. The desired intensity is fed to the input of the algorithm. The output n is the number of peptides that are closest to the given initial value.

![fishy](https://github.com/Zenkin/taste-umami/blob/main/figs/alg.png?raw=true)
