Download Link: https://assignmentchef.com/product/solved-cs161-week-7
<br>
The mode is the value that appears most often in a set of data.  Write a function named <em>findMode</em>​ that takes as parameters an <strong>array</strong>​ ​ of int and the size of the array, and returns a <strong>vector</strong>​    ​ containing the mode(s).  If there is just a single most frequent value, the vector will only contain that one value, but if multiple values tie for maximum frequency, the vector will need to contain all such values.  This includes the case where every number in the array appears only once.  Each mode should appear only once in the vector. The values in the vector that is returned must be in ascending order.   If you need to sort a vector, it’s similar to sorting an array, but specifying the beginning and end of the vector look a little bit different.  If your vector is named ​<em>result</em>​, then it would look like this: “std::sort(result.begin(), result.end());”.

The most straightforward approach is to:

<ol>

 <li>Iterate (loop) through the array to find out what the highest frequency for any value is ​<strong>without</strong>​ worrying about storing any modes.</li>

 <li>Iterate through the array again, this time comparing the counts for each value to the highest frequency that you already found, if the count for a value is the same as the highest frequency, push that value into your results vector. The file must be named: ​<strong>cpp </strong></li>

</ol>





