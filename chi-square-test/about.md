<h1>Chi-Square Test for Industrial Survey</h1>
<p>Chi-square test is a statistical test used to determine if there is a significant association between two categorical variables. In this case, the two variables being analyzed are "company size" and "final response from the industry". The test is performed by calculating the difference between the expected frequencies and the observed frequencies in the contingency table and checking if the difference is significant enough to reject the null hypothesis, which assumes there is no association between the variables. If the p-value of the test is less than a predetermined significance level (usually 0.05), then we reject the null hypothesis and conclude that there is a significant association between the variables</p>

<h3>Frequency Table:</h3>

<table>
  <tr>
    <td> </td>
    <td><b>Yes</b>(Company is Interested to use our proposed system.)</td>
    <td><b>Try</b>(Company is not sure, but positive about our proposed system and wants to try it.)</td>
    <td><b>No</b>(Company is Not Interested to use our proposed system.)</td>
    <td><b>Total</b></td>
  </tr>
  <tr>
    <td><b>Micro</b></td>
    <td>1</td>
    <td>3</td>
    <td>2</td>
    <td>6</td>
  </tr>
  <tr>
    <td><b>Small</b></td>
    <td>1</td>
    <td>9</td>
    <td>9</td>
    <td>19</td>
  </tr>
  <tr>
    <td><b>Medium</b></td>
    <td>13</td>
    <td>14</td>
    <td>1</td>
    <td>28</td>
  </tr>
  <tr>
    <td><b>Large</b></td>
    <td>33</td>
    <td>7</td>
    <td>3</td>
    <td>43</td>
  </tr>
  <tr>
    <td><b>Total</b></td>
    <td>48</td>
    <td>33</td>
    <td>15</td>
    <td>96</td>
  </tr>
 </table>

<h3>Set-up the Null Hypothesis and Alternative Hypothesis</h3>

<p><b>H0:</b>There is no Relationship between Company Size and Response</p>
<p><b>H1:</b>There is a Relationship between Company Size and Response</p>

<h3>Selecting Alpha:</h3>

<p>The significant Level | value of α = 0.05</p>

<h3>Computing the Degree of Freedom:</h3>

<p>Degree of freedom (df) is a statistical concept that represents the number of independent choices or values that can be made in a given problem. It is a measure of the amount of information in a set of data that can be used for statistical inferences and parameter estimation. In hypothesis testing and regression analysis, df is used to calculate the degrees of freedom for test statistics such as t-statistics or chi-squared statistics. The critical values of these test statistics are looked up in tables using the calculated degrees of freedom. The df is calculated as the number of observations minus the number of parameters that must be estimated in a given problem. For example, in a chi-squared test, the df is equal to the number of categories in a contingency table minus 1.</p>

<p>DF = (#rows-1)(#columns-1)</p>
<p>   = (4-1)*(3-1)</p>
<p>   = (3)*(2)</p>
<p>   = 6</p>

<h3>Compute the expected Frequency Table:</h3>

<table>
  <tr>
    <td> </td>
    <td><b>Yes</b>(Company is Interested to use our proposed system.)</td>
    <td><b>Try</b>(Company is not sure, but positive about our proposed system and wants to try it.)</td>
    <td><b>No</b>(Company is Not Interested to use our proposed system.)</td>
    <td><b>Total</b></td>
  </tr>
  <tr>
    <td><b>Micro</b></td>
    <td>3</td>
    <td>2.0625</td>
    <td>0.0375</td>
    <td>6</td>
  </tr>
  <tr>
    <td><b>Small</b></td>
    <td>9.5</td>
    <td>6.53125</td>
    <td>2.96875</td>
    <td>19</td>
  </tr>
  <tr>
    <td><b>Medium</b></td>
    <td>14</td>
    <td>9.625</td>
    <td>4.375</td>
    <td>28</td>
  </tr>
  <tr>
    <td><b>Large</b></td>
    <td>21.5</td>
    <td>14.78125</td>
    <td>6.71875</td>
    <td>43</td>
  </tr>
  <tr>
    <td><b>Total</b></td>
    <td>48</td>
    <td>33</td>
    <td>15</td>
    <td>96</td>
  </tr>
 </table>
