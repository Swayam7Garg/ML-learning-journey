![Before and After scaling](image.png)
here we can see that there are 2 plots one before and one after scaling <br>
<h3>Before scaling-></h3><br>
we can clearly see that Blue Curve (Alcohol):
~10 to 16
and Orange Curve (Malic acid):<br>
The scales are very different, which is bad for many ML algorithms<br>
Alcohol dominates because of its larger numeric range.<br>
<h3>After Standard Scaling-></h3><br>
Both features now have:
Mean ≈ 0
Standard deviation ≈ 1<br>
Even though the shapes (distribution) remain similar, they are now on the same scale, which is critical for:

