---
title: "On the need for structure modelling in sequence prediction"
collection: publications
permalink: /publication/2016-10-01-twomey2016structure
excerpt: 'There is no uniform approach in the literature for modelling sequential correlations in sequence classification problems. It is easy to find examples of unstructured models (e.g. logistic regression) where correlations are not taken into account at all, but there are also many examples where the correlations are explicitly incorporated into a---potentially computationally expensive---structured classification model (e.g. conditional random fields). In this paper we lay theoretical and empirical foundations for clarifying the types of problem which necessitate direct modelling of correlations in sequences, and the types of problem where unstructured models that capture sequential aspects solely through features are sufficient. The theoretical work in this paper shows that the rate of decay of auto-correlations within a sequence is related to the excess classification risk that is incurred by ignoring the structural aspect of the data. This is an intuitively appealing result, demonstrating the intimate link between the auto-correlations and excess classification risk. Drawing directly on this theory, we develop well-founded visual analytics tools that can be applied a priori on data sequences and we demonstrate how these tools can guide practitioners in specifying feature representations based on auto-correlation profiles. Empirical analysis is performed on three sequential datasets. With baseline feature templates, structured and unstructured models achieve similar performance, indicating no initial preference for either model. We then apply the visual analytics tools to the datasets, and show that classification performance in all cases is improved over baseline results when our tools are involved in defining feature representations.'
date: 2016-10-01
venue: 'Machine Learning'
citation: '@article{twomey2016structure,
 abstract = {There is no uniform approach in the literature for modelling sequential correlations in sequence classification problems. It is easy to find examples of unstructured models (e.g. logistic regression) where correlations are not taken into account at all, but there are also many examples where the correlations are explicitly incorporated into a---potentially computationally expensive---structured classification model (e.g. conditional random fields). In this paper we lay theoretical and empirical foundations for clarifying the types of problem which necessitate direct modelling of correlations in sequences, and the types of problem where unstructured models that capture sequential aspects solely through features are sufficient. The theoretical work in this paper shows that the rate of decay of auto-correlations within a sequence is related to the excess classification risk that is incurred by ignoring the structural aspect of the data. This is an intuitively appealing result, demonstrating the intimate link between the auto-correlations and excess classification risk. Drawing directly on this theory, we develop well-founded visual analytics tools that can be applied a priori on data sequences and we demonstrate how these tools can guide practitioners in specifying feature representations based on auto-correlation profiles. Empirical analysis is performed on three sequential datasets. With baseline feature templates, structured and unstructured models achieve similar performance, indicating no initial preference for either model. We then apply the visual analytics tools to the datasets, and show that classification performance in all cases is improved over baseline results when our tools are involved in defining feature representations.},
 author = {Twomey, Niall
and Diethe, Tom
and Flach, Peter},
 doi = {10.1007/s10994-016-5571-y},
 issn = {1573-0565},
 journal = {Machine Learning},
 number = {2},
 pages = {291--314},
 title = {On the need for structure modelling in sequence prediction},
 volume = {104},
 year = {2016}
}

'