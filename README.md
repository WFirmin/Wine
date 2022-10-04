# Wine
For this project I used data on samples of wine from Northern Portugal. The data includes 12 variables: 11
are results from physico-chemical tests on the wine, and the final variable is a quality rating from 1 to 10.
In the data, only ratings from 3 to 8 are present. The aim of the project is to use these physico-chemical
properties of wine to predict its quality.  It’s important to note that the data is dominated by middle values 5 and 6,
with few observations of very good or bad ratings. For this reason, classification will be applied first to two
classes: “Good” signifying a score greater than or equal to 6, and “Bad” signifying a score less than or equal
to 5. Later I will apply classification with six classes, one for each rating level. Finally, I will use regression
methods.
