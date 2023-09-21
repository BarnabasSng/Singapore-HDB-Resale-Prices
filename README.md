# Singapore-HDB-Resale-Prices
This is a project to predict Singapore HDB resale prices based on features of the HDB flat.

This is my first proper project. While pretty simple, I have learned a lot from this project. Here are 2 main takeaways:
1) Importance of a dataset

My model is able to predict housing prices values with an error range of about $48k - considering the median price of a resale flat is about 500k, the error rate is about 8%. However, I feel that this could be further improved. In the importance plot it seems that the top 3 features are more important affect the model far more than the rest. Furthermore, a one-hot encoding of the locations might not be very suitable. Perhaps finding the distance using longitudes and latitudes from the flat to the central business district could be more informative.

2) Writing code in a functional manner

The way I have written the code is not pythonic. The code is not functional at all and to predict new housing prices will require me to manually transform the data again. I should have built a proper data pipeline so that the code is repeatable and scalable.

But all in all, this project definitely allowed me to learn more about building models and the importance of feature data. Perhaps I will return to this in the future to build a better model and create an app based on the model.
