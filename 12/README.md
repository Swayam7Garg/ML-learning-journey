o convert categorical data into a numerical format that can be used by machine learning algorithms. It is particularly useful when dealing with categorical variables that have no ordinal relationship<br>
<h3>Syntax :-</h3><br>
<h5>pandas.get_dummies()</h5><br>
<p>The pandas library provides a simple way to perform one-hot encoding.</p>
<h3>Using sklearn.preprocessing.OneHotEncoder</h3><br>
<p>from sklearn.preprocessing import OneHotEncoder

<h5>Sample data</h5>
data = [['Red'], ['Green'], ['Blue'], ['Red']]

<h5>Initialize encoder</h5>
encoder = OneHotEncoder(sparse=False)

<h5>Fit and transform data</h5>
encoded_data = encoder.fit_transform(data)
print(encoded_data)<p><br>

<h5>Avoid Dummy Variable Trap: In some cases (e.g., linear regression), you may need to drop one of the columns to avoid multicollinearity. This can be done using drop='first' in pandas.get_dummies() or drop='first' in OneHotEncoder.</h5>