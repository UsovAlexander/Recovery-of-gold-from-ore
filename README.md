# Recovery-of-gold-from-ore
The company develops solutions for the efficient operation of industrial enterprises. It is necessary to prepare a prototype of a machine learning model that will predict the recovery rate of gold from gold-bearing ore. We use data with extraction and purification parameters. The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

Tasks:

1. Prepare the data;
2. Conduct an exploratory data analysis;
3. Build and train a model.

To solve the problem, we will introduce a new quality metric — sMAPE (Symmetrical Mean Absolute Percentage Error)

$$sMAPE = \frac{1}{N}\sum_{i=1}^{N} \frac{|y_i - \bar{y_i}|}{|y_i + \bar{y_i}| / 2}$$

$y_i$ -the value of the target attribute for the object with the ordinal number i in the sample on which the quality is measured.  
$\bar{y_i}$ -the prediction value for an object with the ordinal number i, for example, in a test sample.  
$N$ -the number of objects in the sample.
