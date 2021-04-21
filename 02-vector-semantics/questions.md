# Unresolved questions

Group 1: Klara Båstedt, Anna Page, Jacob Coles, Niclas Hertzberg

### 1. SVD and vector space representations

When using SVD, is it necessary to reduce the matrix, or is it possible to keep dimensionality, and how does this affect computing similarity metrics?

We are aware that SVD can be used for some kind of filtering or finding the 'true signal' in data. If we are able to retain dimensionality, how will this modify the matrix, and will it change much?


### 2. Operations on similarities


We have some questions regarding mathematical operations on vectors to derive meaning predictions in part 4. We understand this on a conceptual level, but are wondering about the details.


In the notebook, it says: "We can subtract the normalised vectors for king minus queen and add the resulting vector to man and we hope to get the vector for woman". Would this expressed like this:  `woman = man + (king - queen) `?


Below there is a calculation of  `short = light - (heavy - long) `, which is different from the king/queen example. If it were to follow the same pattern, wouldn't it be  `short = long + (heavy - light) `?
