 Ordinal Encoding and Label Encoding, two very common techniques for converting categorical (non-numeric) data into numeric form, which is necessary for most machine learning algorithms.<br>
 <h3>Label Encoding?</h3><br>
 Label Encoding is a technique where each unique category in a column is assigned an integer value.<br>
 Some ML models (like Linear Regression, KNN) may assume that higher numbers have higher importance — which is not true here, because "Red" isn’t less than "Blue" in any real sense.<br>
 <h3>Ordinal Encoding</h3>
 Ordinal Encoding is used when the categorical variable has a clear order or ranking.<br>
 Used when the categories are ordinal (have a natural order), like ratings, ranks, levels, etc.<br>
<h3> When to Use Which?</h3>
Use Label Encoding when:<br>
There’s no order between categories.<br>
You're using models not sensitive to numerical order (like Decision Trees, Random Forest).<br>
Use Ordinal Encoding when:<br>
The categories have a clear, logical order (like Low < Medium < High).<br>
You want to preserve the rank relationship between categories.<br>