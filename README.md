# Recommendation-System---Transformer-Approach

Recommendation systems are a subclass of information filtering system that seeks to predict the "preference" a user would give to an item.They are primarily used in commercial applications.In this paper,we approach the recommendation systems using the Transformers - firstly, we implement a Behaviour Sequential Transformer model which translates the user behavior into sequences and predicts a rating for each target item. For our second approach we leveraged the Matrix Factorization and enhanced it using BERT embeddings from the items, to create a hybrid approach by combining Content-based filtering with Collaborative filtering approach. Further, we built a K-Nearest Neighbor model to capture the change in item embeddings and used the newly generated embed

Datasets
Our experimental evaluation utilizes two diverse datasets that capture user-item interactions across different domains, enabling comprehensive testing of our approaches on varying feature spaces and dimensionalities:
1. Food.com Recipes Dataset

Scale: 230,186 unique recipes with 1,125,284 user-recipe interactions
Features: Rich metadata including recipe tags, ingredient lists, and detailed descriptions
Domain: Culinary recommendations with complex feature relationships
Interaction Type: User ratings capturing preference signals

2. Restaurant Data with Consumer Ratings

Scale: 1,161 user-restaurant interactions
Features: Multi-dimensional attributes including cuisine types, payment methods, parking availability, and amenity information
Domain: Restaurant recommendations with categorical and binary features
Interaction Type: Consumer ratings reflecting dining experiences

The selection of these datasets enables evaluation across both large-scale (Food.com) and smaller, feature-rich (Restaurant) scenarios, providing insights into model performance under different data characteristics and sparsity conditions.
Key Contributions
This work advances recommendation system research through:

Novel application of Transformer architectures for sequential behavior modeling in recommendations
Hybrid approach combining deep contextual embeddings (BERT) with traditional collaborative filtering
Dynamic embedding adaptation using KNN for capturing temporal changes in item representations
Comprehensive evaluation across domains with varying scale and feature complexity
