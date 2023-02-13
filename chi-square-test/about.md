<h1>Chi-Square Test for Industrial Survey</h1>
<h2>Case - I Company Size v/s Final Response</h2>
<p>Chi-square test is a statistical test used to determine if there is a significant association between two categorical variables. In this case, the two variables being analyzed are <b>"company size"</b> and <b>"final response from the industry".</b> The test is performed by calculating the difference between the expected frequencies and the observed frequencies in the contingency table and checking if the difference is significant enough to reject the null hypothesis, which assumes there is no association between the variables. If the p-value of the test is less than a predetermined significance level (usually 0.05), then we reject the null hypothesis and conclude that there is a significant association between the variables</p>

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
    <td>2</td>
    <td>3</td>
    <td>2</td>
    <td>7</td>
  </tr>
  <tr>
    <td><b>Small</b></td>
    <td>6</td>
    <td>10</td>
    <td>9</td>
    <td>25</td>
  </tr>
  <tr>
    <td><b>Medium</b></td>
    <td>18</td>
    <td>20</td>
    <td>2</td>
    <td>40</td>
  </tr>
  <tr>
    <td><b>Large</b></td>
    <td>37</td>
    <td>11</td>
    <td>6</td>
    <td>54</td>
  </tr>
  <tr>
    <td><b>Total</b></td>
    <td>63</td>
    <td>44</td>
    <td>19</td>
    <td>126</td>
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

<p>The expected frequency in a contingency table is the number of observations that would be expected in each cell if the variables being analyzed are independent. The expected frequency can be calculated using the following equation:</p>

<p><b>Expected Frequency (E) = (Row Total * Column Total) / Grand Total</b></p>
<p>Where,</p>
<ul>
  <li>Row Total is the sum of the observations in a given row</li>
  <li>Column Total is the sum of the observations in a given column</li>
  <li>Grand Total is the sum of all the observations in the contingency table</li>
</ul>

<h3>Compute the χ2 test stistics:</h3>

<p>χ2 = Σ [(Observed frequency - Expected frequency)^2 / Expected frequency]</p>
<p>Where,</p>
<ul>
  <li>Observed frequency is the actual number of observations in a given cell of the contingency table</li>
  <li>Expected frequency is the number of observations that would be expected in that cell if the variables being analyzed are independent, calculated using the formula: (Row Total * Column Total) / Grand Total</li>
  <li>Σ represents the sum of the differences between the observed and expected frequencies squared, divided by the expected frequency, for each cell in the contingency table</li>
  <li></li>
</ul>

<p>Using the above equation, we computed the vaule of χ2,</p>
<p><b><u>χ2 = 25.4759</u></b></p>

<p>Now, we have:</p>
<p>α = 0.05</p>
<p>DF = 6</p>

<p><b><u>χ2(6,0.05) = 12.592</u></b></p>

<p>When we perform a chi-squared test, you check the calculated chi-squared statistic against a critical value to determine if there is a significant association between the variables being analyzed. The critical value is obtained from a chi-squared distribution table, and depends on the level of significance (alpha) and the degrees of freedom (df).</p>

<h3>Summary:</h3>

<p>The chi-squared value of 25.4759 and critical value of 12.592 are calculated based on a chi-squared test. The significance level (alpha) is set to 0.05 and the degrees of freedom (df) is 6.</p>
<p>The comparison of the calculated chi-squared value (25.4759) with the critical value (12.592) is used to test the hypothesis that there is no association between the variables being analyzed. If the calculated chi-squared value is greater than the critical value, it indicates that there is a significant association between the variables and the null hypothesis is rejected.</p>
<p>In this case, with a calculated chi-squared value of 25.4759 and critical value of 12.592, <b><u>the null hypothesis is rejected</u></b>. This means that there is a significant association between the variables being analyzed, based on a significance level of 0.05 and degrees of freedom of 6.</p>

<h2>Case - II Sector v/s Final Response</h2>

<p>A chi-squared test is being performed to examine the relationship between two variables: 'sector' and 'final response.' The contingency table organizes the data and the calculated chi-squared statistic is compared to the critical value to determine significance. If the statistic is greater than the critical value, it means there is a significant association between sector and final response, and the null hypothesis is rejected.</p>

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
    <td>2</td>
    <td>3</td>
    <td>2</td>
    <td>7</td>
  </tr>
  <tr>
    <td><b>Small</b></td>
    <td>6</td>
    <td>10</td>
    <td>9</td>
    <td>25</td>
  </tr>
  <tr>
    <td><b>Medium</b></td>
    <td>18</td>
    <td>20</td>
    <td>2</td>
    <td>40</td>
  </tr>
  <tr>
    <td><b>Large</b></td>
    <td>37</td>
    <td>11</td>
    <td>6</td>
    <td>54</td>
  </tr>
  <tr>
    <td><b>Total</b></td>
    <td>63</td>
    <td>44</td>
    <td>19</td>
    <td>126</td>
  </tr>
 </table>
