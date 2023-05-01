Download Link: https://assignmentchef.com/product/solved-cis450-computer-organization-and-architecture-homework-1
<br>
<strong>(25 points) Problems: </strong>

<strong> </strong>(2.43/2.61) – Using only bit-level and logic operations, write C expressions that yield 1 for the described condition, and 0 otherwise. Assume that x is of type int. You may not use any equality (==) or inequality (!=) tests.




<ol>

 <li>Any bit of x equals 1. _______________________________________________</li>

</ol>




<ol>

 <li>Any bit of x equals 0. _______________________________________________</li>

 <li>Any bit in the least significant byte of x equals 1. _________________________</li>

 <li>Any bit in the least significant byte of x equals 0. _________________________</li>

</ol>

Hint: One solution to part (a.) is: !!x (and, yes, you can use this as your solution :-).







<ol start="2">

 <li>(2.81) – Write C expressions to generate the bit patterns that follow, where <em>a<sup>k</sup></em> represents <em>k </em>repetitions of symbol <em>a</em>. Assume a <em>w-</em>bit data type. Your code may contain references to j and k, representing the values of <em>j </em>and <em>k</em>, but not a parameter representing <em>w</em>.</li>

</ol>




<ol>

 <li>1<em>w-k</em> 0<em>k</em></li>

 <li>0<em>w-k-j</em> 1<em>k</em> 0 <em>j</em></li>

</ol>




For example, if we are dealing with chars, an 8-bit data type, and k = 3, then for a. we want an expression that results in 11111000.










<ol start="3">

 <li>(2.50/2.76/2.77) – Suppose we are given the task of generating code to multiply integer variable x by various different constant factors K. To be efficient, we want to use only the operations +, -, and &lt;&lt;. For the following values of K, write C expressions to perform the multiplication using at most three operations per expression.</li>

</ol>







<ol>

 <li>K = 31: ________________________________________________________</li>

 <li>K = -7: ________________________________________________________</li>

 <li>K = 80: ________________________________________________________</li>

 <li>K = 144: ________________________________________________________</li>

</ol>




Hint: One solution to part (a.) is: (x&lt;&lt;5) – x.
















<ol start="4">

 <li>(2.55/2.82/2.83) – Consider the numbers having a binary representation consisting of an infinite string of the form 0.yyyyyy…, where y is a k-bit sequence. For example, the binary representation of 1/3 is 0.0101010101… (that is, y = 01, and k = 2), while the representation of 1/5 is 0.001100110011… (that is, y = 0011, and k = 4).

  <ol>

   <li>Give a formula in terms of y and k for the value represented by the infinite string. Hint: Consider the effect of shifting the binary point k positions to the right, and do part b. first…</li>

  </ol></li>

</ol>










<ol>

 <li>What is the numeric value of the string for the following values of y? Note that the value of k is implied; e.g., for case i., k = 3, etc.</li>

</ol>




<ol>

 <li>110 ____________________________________________________ ii. 01001 ____________________________________________________ iii. 010111 ____________________________________________________</li>

</ol>




<ol start="5">

 <li>Consider a 16-bit two’s complement representation for signed integers. Fill in the empty boxes in the following table. Spaces in the binary representation are just added to enhance readability.</li>

</ol>







<table width="408">

 <tbody>

  <tr>

   <td width="100"><strong>Number </strong></td>

   <td width="120"><strong>Decimal Representation </strong></td>

   <td width="188"><strong>Binary Representation </strong></td>

  </tr>

  <tr>

   <td width="100"> zero</td>

   <td width="120">0</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100"> </td>

   <td width="120"> </td>

   <td width="188">0000 0000 0000 0101</td>

  </tr>

  <tr>

   <td width="100">twenty five</td>

   <td width="120">25</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100">TMax</td>

   <td width="120">32767</td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100">TMin</td>

   <td width="120"> </td>

   <td width="188">1000 0000 0000 0000</td>

  </tr>

  <tr>

   <td width="100">TMin + TMin</td>

   <td width="120"> </td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100">-TMax</td>

   <td width="120"> </td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100">-TMin</td>

   <td width="120"> </td>

   <td width="188"> </td>

  </tr>

  <tr>

   <td width="100"> </td>

   <td width="120"> </td>

   <td width="188">1111 1111 1110 0111</td>

  </tr>

  <tr>

   <td width="100">negative one</td>

   <td width="120">-1</td>

   <td width="188"> </td>

  </tr>

 </tbody>

</table>

<sup>                </sup>Show work. Hint: 2<sup>15</sup> = 32768, 2<sup>14</sup> = 16384, .. , 2<sup>5</sup> = 32, 2<sup>4</sup> = 16, .. , 2<sup>1</sup> = 2, 2<sup>0</sup> = 1





