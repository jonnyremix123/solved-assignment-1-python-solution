Download Link: https://assignmentchef.com/product/solved-assignment-1-python-solution
<br>
Problem Definition:

Let’s say we have two users, User P and User Q, and they have rated 7 different cell phone brands on a scale of 1 to 10.




<table>

 <tbody>

  <tr>

   <td width="208">Item</td>

   <td width="208">Ratings of User P</td>

   <td width="208">Ratings of User Q</td>

  </tr>

  <tr>

   <td width="208">Apple</td>

   <td width="208">1</td>

   <td width="208">7</td>

  </tr>

  <tr>

   <td width="208">Samsung</td>

   <td width="208">5</td>

   <td width="208">1</td>

  </tr>

  <tr>

   <td width="208">Nokia</td>

   <td width="208">7</td>

   <td width="208">4</td>

  </tr>

  <tr>

   <td width="208">Motorola</td>

   <td width="208">8</td>

   <td width="208">–</td>

  </tr>

  <tr>

   <td width="208">LG</td>

   <td width="208">5</td>

   <td width="208">4</td>

  </tr>

  <tr>

   <td width="208">Sony</td>

   <td width="208">1</td>

   <td width="208">6</td>

  </tr>

  <tr>

   <td width="208">Blackberry</td>

   <td width="208">7</td>

   <td width="208">3</td>

  </tr>

 </tbody>

</table>




In Python, we can depict these ratings as two dictionaries:

<strong><em>UserPRatings</em></strong> = {‘Apple’:1, ‘Samsung’:5, ‘Nokia’:7, ‘Motorola’:8, ‘LG’:5, ‘Sony’:1, ‘Blackberry’:7}

<strong><em>UserQRatings</em></strong> = {‘Apple’:7, ‘Samsung’:1, ‘Nokia’:4, ‘LG’:4, ‘Sony’:6, ‘Blackberry’:3}




We would like to find the Pearson Correlation between these two lists.

Requirement for this Assignment:

This assignment requires you to define and call a Person Correlation function as follows. A framework to get you started has been provided on the next page.

(1) Define a function called <strong><em>pearsonD</em></strong>.

<ul>

 <li>The function must take two (and only two) dictionary parameters – user1ratings and user2ratings – and return the Pearson Correlation between the two user ratings.</li>

 <li>The function must use a single for loop to calculate the Pearson Correlation using the computationally efficient form (similar to Slides 16 and 17 of Knowledge Check 3… but using dictionaries instead of lists):</li>

 <li>The Pearson Correlation calculation must consider an item only if it was rated by both users (similar to how we handled this for Minkowski on Slides 14 and 15 of Knowledge Check 4)</li>

</ul>

(2) Then call this function for UserPRatings and UserQRatings defined above, and print the person correlation value.

Some things to keep in mind as you code:

<ul>

 <li>Make your code readable – for instance, use meaningful variable names and comments.</li>

 <li>Make your code elegant – for instance, balance the number of variables you introduce – too many or too few make your code difficult to debug, read, and maintain.</li>

 <li>Make your output readable and user-friendly</li>

</ul>

Framework for coding:

Submission:

Once you have written up the script, save it as follows: &lt;FirstName&gt;&lt;LastName&gt;Assignment1.py.

<em>[Example: HinaAroraAssignment1.py]</em>

Submit the script by uploading the above python script. Note: upload the actual script – DO NOT attach a screenshot of the script!

The submitted script will be run <strong><u>as-is</u></strong> for grading. Points will be deducted for scripts that:

<ul>

 <li>do not adhere to all of the requirements called out under the requirements section above</li>

 <li>are difficult to read/follow</li>

 <li>don’t compile/run</li>

 <li>don’t have all the various pieces of code required</li>

 <li>have hard-code values instead of using variables</li>

 <li>have logical errors</li>

 <li>don’t result in the expected output</li>

 <li>don’t have user-friendly output</li>

</ul>

Hint:

If you have coded up this assignment correctly, you should end up with a Pearson Correlation of -0.7307.