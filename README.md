### Build a Simple Recommender System Using Surprise

Recommender Systems are used to predict user preferences or we can say that these are systems that help people find things when the manual process of selection is a little bit challenging because of too many choices or alternatives. The best examples are Amazon recommending us the next book to read or Netflix suggesting the next movie to watch.
There are three types of recommender systems.
<ul>
    <li>Collaborative filtering</li>
    <li>Content-based filtering</li>
    <li>Hybrid recommender system</li>
</ul>
We are going to build a recommender system using the collaborative filtering technique. 
Collaborative filtering is the technique of making predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).

[Surprise](https://github.com/NicolasHug/Surprise) is a Python [scikit](https://www.scipy.org/scikits.html) for building and testing recommender systems that deal with explicit rating data. 
We will make use of this library for building the collaborative filtering based recommender system.
