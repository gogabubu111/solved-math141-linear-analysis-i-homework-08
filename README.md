Download Link: https://assignmentchef.com/product/solved-math141-linear-analysis-i-homework-08
<br>
Construct examples of linear transformation that satisfy the following requirements. If no such examples are possible, explain why. (Hint: Problems #6-8 of Homework 06 help you connect one-to-one or onto linear transformations to properties of matrices.)

<table width="580">

 <tbody>

  <tr>

   <td width="68"></td>

   <td width="171">one-to-one but not onto</td>

   <td width="171">onto but not one-to-one</td>

   <td width="171">both one-to-one and onto</td>

  </tr>

  <tr>

   <td width="68"></td>

   <td width="171"></td>

   <td width="171"></td>

   <td width="171"></td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li>(<em>Strang </em><em>2.1 #2</em>) Which of the following subsets of R<sup>3 </sup>are actually subspaces? For each subspace you find, find a basis for that subspace. Describe your reasoning.

  <ul>

   <li>The plane of vectors with first component <em>b</em><sub>1 </sub>= 0.</li>

   <li>The plane of vectors<em><sup>~</sup></em><em>b </em>with first component <em>b</em><sub>1 </sub>= 1.</li>

   <li>The vectors <em><sup>~</sup></em><em>b </em>with <em>b</em><sub>2</sub><em>b</em><sub>3 </sub>= 0 (notice that this is the union of two subspaces, the plane <em>b</em><sub>2 </sub>= 0 and the plane <em>b</em><sub>3 </sub>= 0).</li>

   <li>All linear combinations of two given vectors and  .</li>

   <li>The plane of vectors<em><sup>~</sup></em><em>b </em>that satisfy <em>b</em><sub>3 </sub>− <em>b</em><sub>2 </sub>+ 3<em>b</em><sub>1 </sub>= 0.</li>

  </ul></li>

 <li>Determine each of the following statements true or false. Explain your reasoning.

  <ul>

   <li>{<em><sup>~</sup></em>0} is a vector subspace of any R<em><sup>n</sup></em>, where<em><sup>~</sup></em>0 has <em>n </em>zeroes as coordinates.</li>

   <li>Any straight line in R<sup>2 </sup>is a vector subspace of R<sup>2</sup>.</li>

   <li>Any two-dimensional plane going through the origin in R<sup>3 </sup>is a vector subspace of R<sup>3</sup>.</li>

  </ul></li>

 <li>(<em>added on Wednesday</em>) Finish the worksheet in lecture titled ”Basis for <em>N</em>(<em>A</em>) and <em>C</em>(<em>A</em>)”, a copy of which is posted on CatCourses. Turn in a digital copy of your solution together with the rest of this homework set, <strong>and bring a hard copy of your solutions to class on Monday.</strong></li>

 <li>(<em>revised on Wednesday</em>) <strong><em>The dimension of a vector subspace </em></strong><strong>W<em>, denote by </em></strong>dim<strong>W</strong><strong><em>, is defined to be the number of vectors in its basis.</em></strong>

  <ul>

   <li>For the matrix in the worksheet,. what is dim<em>N</em>(<em>A</em>)? What is dim<em>C</em>(<em>A</em>)?</li>

   <li>If <em>A </em>is an <em>m</em>-by-<em>n </em>matrix with rank <em>r</em>. What is dim<em>N</em>(<em>A</em>)? What is dim<em>C</em>(<em>A</em>). Explain your reasoning. (Hint: review the worksheet.)</li>

  </ul></li>

 <li>(<em>postponed to next week</em>) <em>T </em>: R<em><sup>n </sup></em>→ R<em><sup>m </sup></em>is a linear transformation.

  <ul>

   <li>Is ker(<em>T</em>) a subspace of R<em><sup>n</sup></em>?. Explain your reasoning. If yes, how can you find a basis for ker(<em>T</em>)?</li>

   <li>Is range(<em>T</em>) a subspace of R<em><sup>m</sup></em>?. Explain your reasoning. If yes, how can you find a basis for range(<em>T</em>)?</li>

  </ul></li>

</ol>

(Hint: Connect ker(<em>T</em>) and range(<em>T</em>) to column space and nullspace of some matrix.)

MATH 141: Linear Analysis I                                              Homework 08                                                                               <em>Fall 2019</em>

<ol start="7">

 <li>Follow the steps below to prove the theorem: If {<em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n</sub></em>} is a basis for R<em><sup>n</sup></em>, then any vector <em>~x </em>in R<em><sup>n </sup></em>can be written as a linear combination of <em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n </sub></em>in a unique way.

  <ul>

   <li>Which requirement for {<em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n</sub></em>} to be a basis ensures that <em>~x </em>can be written as <em>some </em>linear combination of <em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n</sub></em>?</li>

   <li>Suppose that <em>~x </em>can be written as a linear combination of <em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n </sub></em>in two different ways. That is,</li>

  </ul></li>

</ol>

<em>~x </em>= <em>c</em><sub>1</sub><em>~e</em><sub>1 </sub>+ <em>c</em><sub>2</sub><em>~e</em><sub>2 </sub>+ ··· + <em>c<sub>n</sub>~e<sub>n</sub>,       </em>and      <em>~x </em>= <em>d</em><sub>1</sub><em>~e</em><sub>1 </sub>+ <em>d</em><sub>2</sub><em>~e</em><sub>2 </sub>+ ··· + <em>d<sub>n</sub>~e<sub>n</sub></em>

where all the <em>c</em>’s are not the same as all the <em>d</em>’s. By calculating <em>~x </em>− <em>~x</em>, show that one requirement for {<em>~e</em><sub>1</sub><em>,~e</em><sub>2</sub><em>,…,~e<sub>n</sub></em>} to be a basis has been violated.

<ul>

 <li>Explain briefly why putting parts (a) and (b) together leads to a proof of the theorem.</li>

</ul>