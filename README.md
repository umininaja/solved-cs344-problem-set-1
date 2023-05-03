Download Link: https://assignmentchef.com/product/solved-cs344-problem-set-1
<br>
<ol>

 <li><strong>Big-O notation. </strong>We have learnt big-O notation to compare the growth rates of functions, this exercise helps you to better understand its definition and properties.</li>

</ol>

(a) (10 points) Suppose <em>n </em>is the input size, we have the following commonly seen functions in complexity analysis: <em>f</em><sub>1</sub>(<em>n</em>) = 1<em>,f</em><sub>2</sub>(<em>n</em>) = log<em>n,f</em><sub>3</sub>(<em>n</em>) = <em>n,f</em><sub>4</sub>(<em>n</em>) = <em>n</em>log<em>n,f</em><sub>5</sub>(<em>n</em>) = <em>n</em><sup>2</sup><em>,f</em><sub>6</sub>(<em>n</em>) = 2<em><sup>n</sup></em>. Intuitively, the growth rate of the functions satisfy 1 <em>&lt; </em>log<em>n &lt; n &lt; n</em>log<em>n &lt; n</em><sup>2 </sup><em>&lt; </em>2<em><sup>n</sup></em>. Prove this is true.

[<strong>Hint</strong>: You are expected to prove the following asymptotics by using the definition of big-O notation: 1 = <em>O</em>(log<em>n</em>)<em>,</em>log<em>n </em>= <em>O</em>(<em>n</em>)<em>,n </em>= <em>O</em>(<em>n</em>log<em>n</em>)<em>,n</em>log<em>n </em>= <em>O</em>(<em>n</em><sup>2</sup>)<em>,n</em><sup>2 </sup>= <em>O</em>(2<em><sup>n</sup></em>). <strong>Note</strong>: Chap 3.2 of our textbook provides some math facts in case you need.]

Answer:

<strong>Using The Definition</strong>:<em>f</em>(<em>n</em>) is <em>O</em>(<em>g</em>(<em>n</em>)) if and only if there exists positive constants ”C” and ”k” such that |<em>f</em>(<em>n</em>)| <em>&lt;</em>= <em>C </em>∗ |<em>g</em>(<em>n</em>)| for all <em>n &gt;</em>= <em>k</em>.

<strong>Note: All of the log is base on 10.</strong>

<strong>let </strong><em>f</em>(<em>n</em>) = 1<em>,g</em>(<em>n</em>) = log<em>n </em>1 ≤ <em>C </em>∗ log<em>n </em>(for all <em>n </em>≤ <em>k</em>) choose <em>k </em>= 10

1 ≤ <em>C </em>∗ log<em>n </em>(for all <em>n </em>≤ 10)

(for all <em>n </em>≤ 10) choose <em>C </em>= 1

1 ≤ 1 ∗ log<em>n </em>(for all <em>n </em>≤ 10) 1 ≤ log<em>n </em>(for all <em>n </em>≤ 10) that always true. So <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies 1 = <em>O</em>(log<em>n</em>)

<strong>let </strong><em>f</em>(<em>n</em>) = log<em>n,g</em>(<em>n</em>) = <em>n </em>log<em>n </em>≤ <em>C </em>∗ <em>n </em>(for all <em>n </em>≤ <em>k</em>) choose <em>k </em>= 10 log<em>n </em>≤ <em>C </em>∗ <em>n </em>(for all <em>n </em>≤ 10)

(for all <em>n </em>≤ 10) choose

log<em>n </em>≤ <em>C </em>∗ <em>n </em>(for all <em>n </em>≤ 10) (for all <em>n </em>≤ 10)  (for all <em>n </em>≤ 10) that always true. So <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies log<em>n </em>= <em>O</em>(<em>n</em>)

<strong>let </strong><em>f</em>(<em>n</em>) = <em>n,g</em>(<em>n</em>) = <em>n</em>log<em>n n </em>≤ <em>C </em>∗ <em>n</em>log<em>n</em>(for all <em>n </em>≤ <em>k</em>) choose <em>k </em>= 10 <em>n </em>≤ <em>C </em>∗ <em>n </em>∗ log<em>n</em>(for all <em>n </em>≤ 10) 1 ≤ <em>C </em>log<em>n </em>(for all <em>n </em>≤ 10) choose <em>C </em>= 1 <em>n </em>≤ <em>C </em>∗ <em>n </em>∗ log<em>n</em>(for all <em>n </em>≤ 10)

1 ≤ log<em>n </em>(for all <em>n </em>≤ 10) that always true. So <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies <em>n </em>= <em>O</em>(<em>n </em>∗ log<em>n</em>)

<strong>let </strong><em>f</em>(<em>n</em>) = <em>n</em>log<em>n,g</em>(<em>n</em>) = <em>n</em><sup>2 </sup><em>n</em>log<em>n </em>≤ <em>C </em>∗ <em>n</em><sup>2 </sup>(for all <em>n </em>≤ <em>k</em>) choose <em>n </em>= 10 <em>n</em>log<em>n </em>≤ <em>C </em>∗ <em>n</em><sup>2 </sup>(for all <em>n </em>≤ 10) log<em>n </em>≤ <em>C </em>∗ <em>n </em>(for all <em>n </em>≤ 10)

(for all <em>n </em>≤ 10) choose

(for all <em>n </em>≤ 10)

(for all <em>n </em>≤ 10)  (for all <em>n </em>≤ 10) that always true. So <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies <em>n</em>log<em>n </em>= <em>O</em>(<em>n</em><sup>2</sup>)

<strong>let </strong><em>f</em>(<em>n</em>) = <em>n</em><sup>2</sup><em>,g</em>(<em>n</em>) = 2<em><sup>n </sup>n</em><sup>2 </sup>≤ <em>C </em>∗ 2<em><sup>n </sup></em>(for all <em>n </em>≤ <em>k</em>) choose <em>k </em>= 1 <em>n</em><sup>2 </sup>≤ <em>C </em>∗ 2<em><sup>n </sup></em>(for all <em>n </em>≤ 1)

(for all <em>n </em>≤ 1) choose

(for all <em>n </em>≤ 1)

(for all <em>n </em>≤ 1)

(for all <em>n </em>≤ 1) that always true. So <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies <em>n</em><sup>2 </sup>= <em>O</em>(2<em><sup>n</sup></em>)

In sum, we can get that he growth rate of the functions satisfy 1 <em>&lt; </em>log<em>n &lt; n &lt; n</em>log<em>n &lt; n</em>2 <em>&lt; </em>2<em>n</em>.

(b) (10 points) Let <em>f,g </em>: <em>N </em>→ <em>R</em><sup>+</sup>, prove that <em>O</em>(<em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)) = <em>O</em>(max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}).

[<strong>Hint</strong>: The key is max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) ≤ 2 · max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}. <strong>Note</strong>: Proving this will help you to understand why we can leave out the insignificant parts in big-O notation and only keep the dominate part, e.g., <em>O</em>(<em>n</em><sup>2</sup>+<em>n</em>log<em>n</em>+<em>n</em>) = <em>O</em>(<em>n</em><sup>2</sup>).] Answer:

Given <em>f,g </em>: <em>N </em>→ <em>R</em><sup>+ </sup><em>f</em>(<em>n</em>) ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)<em>,g</em>(<em>n</em>) ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)

Therefore, max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)

Let max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} = <em>f</em>(<em>n</em>)

Therefore, <em>g</em>(<em>n</em>) ≤ max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}

Thus, <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) ≤ 2max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}

Let max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} = <em>g</em>(<em>n</em>)

Therefore, <em>f</em>(<em>n</em>) ≤ max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}

Thus, <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) ≤ 2max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}

From above, we can get that max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) ≤ 2max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}

From <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) ≤ 2max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} for every <em>n </em>≥ 1 We can get that <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) = <em>O</em>(max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}.

From max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} ≤ <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) for every <em>n </em>≥ 1

We can get that max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} = <em>f</em>(<em>n</em>) = <em>g</em>(<em>n</em>)

In sum, <em>O</em>(<em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)) = <em>O</em>(max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)}), for <em>f,g </em>: <em>N </em>→ <em>R</em><sup>+</sup>.

<ol start="2">

 <li><strong>Proof of correctness. </strong>(10 points) We have the following algorithm that sorts a list of integers to ascending order. Prove that this algorithm is correct. [<strong>Hint: </strong>You are expected to use mathematical induction to provide a rigorous proof.]</li>

</ol>

Answer:

<strong>Invariant of outer loop</strong>: At start of iteration the outer for loop,<em>A</em>[0 : <em>i </em>− 1] is sorted. <strong>Invariant of inner loop</strong>: at start of iteration the inner for loop, <em>A</em>[<em>min<sub>i</sub>ndex</em>] is the smallest value from <em>A</em>[<em>i </em>: <em>j</em>].

<strong>Algorithm 1: </strong>Sort a list

<strong>Input: </strong>Unsorted list <em>A </em>= [<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>] of <em>n </em>items

<strong>Output: </strong>Sorted list items in ascending order <strong>for </strong><em>i </em>= 0<em>, i &lt; n </em>− 1<em>, i</em>++ <strong>do</strong>

<strong>Initialization</strong>:

Prior to the first iteration of outer loop, A[0] is the <em>A</em>[<em>min</em>−<em>index</em>], the array <em>A</em>[1 : <em>i</em>−1] is empty.

Prior to the first iteration of inner loop, the sub-array <em>A</em>[<em>j </em>: <em>n</em>] contains the single value.

<strong>Maintenance</strong>:

<table>

 <tbody>

  <tr>

   <td width="102"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

The invariant holds at the start of the iteration <em>j </em>= <em>i </em>+ 1 of the inner for loop. At the start of the first iteration, A[i]is the <em>A</em>[<em>min<sub>i</sub>ndex</em>], then comparing the all elements with <em>A</em>[<em>min<sub>i</sub>ndex</em>] from <em>A</em>[<em>j </em>: <em>n</em>]. The smallest value instead of the <em>A</em>[<em>min<sub>i</sub>ndex</em>], became the new <em>A</em>[<em>min<sub>i</sub>ndex</em>].

At the end of each outer loop, swapping the <em>A</em>[<em>i</em>]<em>,A</em>[<em>min<sub>i</sub>ndex</em>]. Therefore, the sub array is sorted from <em>A</em>[0 : <em>i</em>].

<strong>Termination</strong>:

When <em>i </em>= <em>n </em>− 1,the outer for loop is ended. All values in <em>A</em>[0 : <em>n </em>− 2] are sorted and <em>A</em>[<em>length </em>− 1] is biggest value from <em>A</em>[0 : <em>n </em>− 1], therefore, all values in <em>A</em>[0 : <em>n </em>− 1] are sorted.

when <em>i </em>= <em>n </em>− 1<em>,j </em>= <em>n</em>, the inner for loop is ended. <em>A</em>[<em>n </em>− 1] is smallest value from <em>a</em>[<em>n </em>− 1 : <em>n</em>].

<ol start="3">

 <li><strong>Practice the recursion tree. </strong>(10 points) We have already had a recurrence relation of an algorithm, which is <em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n/</em>2) + 3<em>n</em>. Solve this recurrence relation, i.e. express it as <em>T</em>(<em>n</em>) = <em>O</em>(<em>f</em>(<em>n</em>)), by using the recursion tree method. [<strong>Note</strong>: If you find it difficult to draw a picture using Latex directly, you can draw it using Microsoft PowerPoint and then save it as a picture file (.png or .jpg), or you can draw on a piece of paper by hand, and take a picture of it using your phone. Then, you can insert the picture into your latex code and compile it into the final PDF submission. The following code shows an example of how to insert figures in latex code, as shown in Figure 1.]</li>

</ol>

Answer:

Figure 1: recursion tree.

<ol start="4">

 <li><strong>Practice with the iteration method. </strong>We have already had a recurrence relation of an algorithm, which is <em>T</em>(<em>n</em>) = 4<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>.</li>

</ol>

(a) (5 points) Solve this recurrence relation, i.e., express it as <em>T</em>(<em>n</em>) = <em>O</em>(<em>f</em>(<em>n</em>)), by using the iteration method.

Answer:

<strong>Note: all the log is base on 2.</strong>

Given <em>T</em>(<em>n</em>) = 4<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>.

Using the Iteration method: <em>T</em>(<em>n/</em>2) = 4<em>T</em>(<em>n/</em>2<sup>2</sup>) + (<em>n/</em>2)<sup>2 </sup>log(<em>n/</em>2).

<em>T</em>(<em>n</em>) = 4<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>

<em>T</em>(<em>n</em>) = 4[4<em>T</em>(<em>n/</em>2<sup>2</sup>) + (<em>n/</em>2)<sup>2 </sup>log(<em>n/</em>2)] + <em>n</em><sup>2 </sup>log<em>n</em>.

<em>T</em>(<em>n</em>) = 4<sup>2</sup><em>T</em>(<em>n/</em>2<sup>2</sup>) + <em>n</em><sup>2 </sup>log(<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>

<em>T</em>(<em>n</em>) = 4<sup>2</sup><em>T</em>(<em>n/</em>4) + <em>n</em><sup>2</sup>[log(<em>n/</em>2) + log<em>n</em>]

As same we get that: <em>T</em>(<em>n/</em>4) = 4<em>T</em>(<em>n/</em>2<sup>3</sup>) + (<em>n/</em>2<sup>2</sup>)<sup>2 </sup>log(<em>n/</em>2<sup>2</sup>)

<em>T</em>(<em>n</em>) = 4<sup>2</sup><em>T</em>(<em>n/</em>4) + <em>n</em><sup>2</sup>(log(<em>n/</em>2) + log<em>n</em>)

<em>T</em>(<em>n</em>) = 4<sup>2</sup>[4<em>T</em>(<em>n/</em>2<sup>3</sup>) + (<em>n/</em>2<sup>2</sup>)<sup>2 </sup>log(<em>n/</em>2<sup>2</sup>)] + <em>n</em><sup>2 </sup>log(<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>

<em>T</em>(<em>n</em>) = 4<sup>3 </sup>∗ <em>T</em>(<em>n/</em>2<sup>3</sup>) + <em>n</em><sup>2 </sup>log(<em>n/</em>2<sup>2</sup>) + <em>n</em><sup>2 </sup>log<em>n/</em>2) + <em>n</em><sup>2 </sup>log<em>n</em>

<em>T</em>(<em>n</em>) = 4<sup>3 </sup>∗ <em>T</em>(<em>n/</em>2<sup>3</sup>) + <em>n</em><sup>2</sup>[log(<em>n/</em>2<sup>2</sup>) + log<em>n/</em>2) + log<em>n</em>]

In sum,we can find that

Let <em>n </em>= 1<em>,T</em>(1) = <em>n/</em>2<em><sup>k </sup></em>= 1

<em>k</em>

(b) (5 points) Prove, by using mathematical induction, that the iteration rule you have observed in 4(a) is correct and you have solved the recurrence relation correctly. [<strong>Hint</strong>: You can write out the general form of <em>T</em>(<em>n</em>) at the iteration step <em>t</em>, and prove that this form is correct for any iteration step <em>t </em>by using mathematical induction. Then by finding out the eventual number of <em>t </em>and substituting it into your general form of <em>T</em>(<em>n</em>), you get the <em>O</em>(·) notation of <em>T</em>(<em>n</em>).]

Answer:

Using the mathematical introduction

Base case: let <em>n </em>= 2<em>,T</em>(2) = 4<em>T</em>(2<em>/</em>2) + 4log2 = 4<em>T</em>(1) + 4 = 4<em>c </em>+ 4 ≤ <em>k</em>(4log<sup>2</sup>(2)) So, <em>T</em>(2) = <em>O</em>(<em>n</em><sup>2 </sup>log<sup>2</sup>(2))is true. Assume <em>T</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>2 </sup>∗ log<sup>2 </sup><em>n</em>)is true.

let<em>n </em>= <em>k </em>+ 1

<em>T</em>(<em>k </em>+ 1) = 4<em>T</em>(<em>k </em>+ 1<em>/</em>2) + (<em>k </em>+ 1)<sup>2 </sup>∗ log(<em>k </em>+ 1)

<em>T</em>(<em>k </em>+ 1) = 4[(<em>k </em>+ 1<em>/</em>2)<sup>2 </sup>log<sup>2</sup>(<em>k </em>+ 1<em>/</em>2)] + (<em>k </em>+ 1)<sup>2 </sup>∗ log(<em>k </em>+ 1)

<em>T</em>(<em>k </em>+ 1) = (<em>k </em>+ 1)<sup>2 </sup>log<sup>2</sup>(<em>k </em>+ 1<em>/</em>2) + (<em>k </em>+ 1)<sup>2 </sup>∗ log(<em>k </em>+ 1)

<em>T</em>(<em>k </em>+ 1) = (<em>k </em>+ 1)<sup>2 </sup>∗ (log<sup>2</sup>(<em>k </em>+ 1<em>/</em>2)] + log(<em>k </em>+ 1)) ≤ <em>k</em>(<em>k </em>+ 1)<sup>2 </sup>∗ log<sup>2</sup>(<em>k </em>+ 1)

(log<sup>2</sup>(<em>k </em>+ 1<em>/</em>2) + log(<em>k </em>+ 1)) ≤ <em>k</em>log<sup>2</sup>(<em>k </em>+ 1)

(log<sup>2</sup>(<em>k </em>+ 1) − log<sup>2</sup>(2) + log(<em>k </em>+ 1)) ≤ <em>k</em>log<sup>2</sup>(<em>k </em>+ 1) is true. So, we get that when<em>n </em>= <em>k </em>+ 1<em>,T</em>(<em>k </em>+ 1) = <em>O</em>((<em>k </em>+ 1)<sup>2 </sup>∗ log<sup>2</sup>(<em>k </em>+ 1)) Thus, <em>T</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>2 </sup>∗ log<sup>2</sup>(<em>n</em>)) is true.

<ol start="5">

 <li><strong>Practice with the Master Theorem</strong>. Solve the following recurrence relations; i.e. express each one as <em>T</em>(<em>n</em>) = <em>O</em>(<em>f</em>(<em>n</em>)) for the tightest possible function <em>f</em>(<em>n</em>) using the Master Theorem, and give a short justification. Unless otherwise stated, assume <em>T</em>(1) = 1.</li>

</ol>

<strong>[To see the level of detail expected, we have worked out the first one for you.]</strong>

(z) <em>T</em>(<em>n</em>) = 6<em>T</em>(<em>n/</em>6) + 1. We apply the master theorem with <em>a </em>= <em>b </em>= 6 and with <em>d </em>= 0. We have <em>a &gt; b<sup>d</sup></em>, and so the running time is <em>O</em>(<em>n</em><sup>log</sup><sup>6</sup><sup>(6)</sup>) = <em>O</em>(<em>n</em>).

√

<ul>

 <li>(5 points) <em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n/</em>4) + <em>n</em></li>

</ul>

Answer:

Using master method <em>T</em>(<em>n</em>) = <em>a </em>∗ <em>T</em>(<em>n/b</em>) + <em>O</em>(<em>n<sup>d</sup></em>)

√ <em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n/</em>4) +   <em>n </em>we get that <em>a </em>= 3<em>,b </em>= 4<em>,d </em>= 1<em>/</em>2 <em>b</em><em>d </em>= 41<em>/</em>2 = 2<em>,a &gt; b</em><em>d</em>

so, <em>O</em>(<em>n</em>log<em><sub>b</sub></em>(<em>a</em>) = <em>O</em>(<em>n</em>log<sub>4</sub>(3))

<ul>

 <li>(5 points) <em>T</em>(<em>n</em>) = 7<em>T</em>(<em>n/</em>2) + Θ(<em>n</em><sup>3</sup>)</li>

</ul>

Answer:

<em>T</em>(<em>n</em>) = 7<em>T</em>(<em>n/</em>2) + Θ(<em>n</em><sup>3</sup>) <em>a </em>= 7<em>,b </em>= 2<em>,d </em>= 3 <em>b<sup>d </sup></em>= 2<sup>3 </sup>= 8<em>,a &lt; b<sup>d</sup></em>

So, <em>O</em>(<em>n<sup>d</sup></em>) = <em>O</em>(<em>n</em><sup>3</sup>)

<ul>

 <li>(5 points) <em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n/</em>3)+<em>n<sup>c</sup></em>, where <em>c </em>≥ 1 is a constant that doesn’t depend on <em>n</em>.</li>

</ul>

Answer:

<em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n/</em>3) + <em>n<sup>c </sup>a </em>= 2<em>,b </em>= 3<em>,d </em>= <em>c </em>≥ 1 <em>b<sup>d </sup></em>≥ 3 so, <em>a &lt; b<sup>d</sup></em>, <em>O</em>(<em>n<sup>d</sup></em>) = <em>O</em>(<em>n<sup>c</sup></em>)

<ol start="6">

 <li><strong>Proof of the Master Theorem. </strong>(15 points) Now that we have practiced with the recursion tree method, the iteration method, and the Master method. The Master Theorem states that, suppose <em>T</em>(<em>n</em>) = <em>a </em> <em>T</em>(<em>n/b</em>) + <em>O</em>(<em>n<sup>d</sup></em>), we have:</li>

</ol>

<sup></sup><em>O</em>(<em>n<sup>d </sup></em>log<em>n</em>)<em>,          if a </em>= <em>b<sup>d</sup></em>

 <em>d                                       d</em>

<em>T</em>(<em>n</em>) =        <em>O</em>(<em>n </em>)<em>,        if a &lt; b</em>

<em>O</em>(<em>n</em>log<em>b </em><em>a</em>)<em>,        if a &gt; b</em><em>d</em>

Prove that the Master Theorem is true by using either the recursion tree method or the iteration method.

Answer:

Assume <em>n </em>= <em>b<sup>k</sup>andO</em>(<em>n<sup>d</sup></em>) = <em>n<sup>d</sup></em>

<em>T</em>(<em>n</em>) = <em>T</em>(<em>b</em><em>k</em>) = <em>a </em>∗ <em>T</em>(<em>b</em><em>k</em>−1 + <em>b</em><em>k</em>∗<em>d </em>= <em>a</em>(<em>a </em>∗ <em>T</em>(<em>b</em><em>k</em>−2 + <em>b</em><em>d</em>(<em>k</em>−1)) + <em>b</em><em>k</em>∗<em>d</em>

<em>T</em>(<em>n</em>) = <em>a</em>2 ∗ <em>T</em>(<em>b</em><em>k</em>−2) + <em>ab</em><em>d</em>(<em>k</em>−1) + <em>b</em><em>k</em>∗<em>d</em>

<em>T</em>(<em>n</em>) = <em>a</em>3 ∗ <em>T</em>(<em>b</em><em>k</em>−3 + <em>a</em>2 ∗ <em>T</em>(<em>b</em><em>d</em>(<em>k</em>−2)) + <em>ab</em><em>d</em>(<em>k</em>−1) + <em>b</em><em>k</em>∗<em>d </em>In sum, let <em>p </em>= <em>b<sup>d</sup>,q </em>= <em>a/r p</em><em>k </em>= <em>b</em><em>b</em>∗<em>k </em>= (<em>b</em><em>k</em>)<em>d </em>= <em>n</em><em>d</em><em>,a</em><em>k </em>= <em>a</em>log<em><sub>b</sub></em>(<em>n</em>) = <em>n</em>log<em><sub>b</sub></em>(<em>a</em>)

So, we get that

There are three situations in for different values of q. when <em>a </em>= <em>b<sup>d</sup>,d </em>= log<em><sub>b</sub></em>(<em>a</em>)<em>,p </em>= <em>a</em>

Therefore,

when <em>a &lt; b<sup>d</sup>,d &gt; </em>log<em><sub>b</sub></em>(<em>a</em>)<em>,p &gt; a</em>

<em>k</em>

Therefore,

when <em>a &gt; b<sup>d</sup>,d &lt; </em>log<em><sub>b</sub></em>(<em>a</em>)<em>,p &lt; a</em>

Therefore,

<ol start="7">

 <li><strong>Algorithm design. </strong>Each of <em>n </em>users spends some time on a social media site. For each <em>i </em>= 1<em>,…,n</em>, user <em>i </em>enters the site at time <em>a<sub>i </sub></em>and leaves at time <em>b<sub>i </sub></em>≥ <em>a<sub>i</sub></em>. You are interested in the question: how many distinct pairs of users are ever on the site at the same time? (Here, the pair (<em>i,j</em>) is the same as the pair (<em>j,i</em>)).</li>

</ol>

Example: Suppose there are 5 users with the following entering and leaving times:

<table width="227">

 <tbody>

  <tr>

   <td width="47">User</td>

   <td width="89">Enter time</td>

   <td width="90">Leave time</td>

  </tr>

  <tr>

   <td width="47">1</td>

   <td width="89">1</td>

   <td width="90">4</td>

  </tr>

  <tr>

   <td width="47">2</td>

   <td width="89">2</td>

   <td width="90">5</td>

  </tr>

  <tr>

   <td width="47">3</td>

   <td width="89">7</td>

   <td width="90">8</td>

  </tr>

  <tr>

   <td width="47">4</td>

   <td width="89">9</td>

   <td width="90">10</td>

  </tr>

  <tr>

   <td width="47">5</td>

   <td width="89">6</td>

   <td width="90">10</td>

  </tr>

 </tbody>

</table>

Then, the number of distinct pairs of users who are on the site at the same time is three: these pairs are (1<em>,</em>2), (4<em>,</em>5), (3<em>,</em>5). (Drawing the intervals on a number line may make this easier to see).

(a) (10 points) Given input (<em>a</em><sub>1</sub><em>,b</em><sub>1</sub>)<em>,</em>(<em>a</em><sub>2</sub><em>,b</em><sub>2</sub>)<em>,…,</em>(<em>a<sub>n</sub>,b<sub>n</sub></em>) as above in no particular order (i.e., not sorted in any way), describe a straightforward algorithm that takes Θ(<em>n</em><sup>2</sup>)time to compute the number of pairs of users who are ever on the site at the same time, and explain why it takes Θ(<em>n</em><sup>2</sup>)-time. <strong>[We are expecting pseudocode and a brief justification for its runtime.]</strong>

Answer:

input: List containing the time interval of each users (<em>a</em>1<em>,b</em>1)<em>,</em>(<em>a</em>2<em>,b</em>2)<em>,</em>(<em>a</em>3<em>,b</em>3)<em>,…</em>(<em>an,bn</em>). There are n users.

for <em>i </em>= 0<em>,i &lt; n </em>− 1<em>,i </em>+ + (outer loop) for <em>j </em>= <em>i </em>+ 1<em>,j &lt; n,j </em>+ + (inner loop) if <em>A</em>[<em>ai</em>] <em>&gt;</em>= <em>A</em>[<em>bj</em>]<em>orA</em>[<em>bi</em>] <em>&lt;</em>= <em>A</em>[<em>aj</em>]

Output: (<em>i,j</em>)

We compare the each user’s time intervals with all the time intervals of the left users. if we find the overlap, we will output the serial numbers of two users with overlapping time.

Time complexity = <em>n </em>− 1 + <em>n </em>− 2 + <em>n </em>− 3 + <em>n </em>− 4 + <em>… </em>+ 1 = <em>n </em>∗ (<em>n </em>− 1)<em>/</em>2 = <em>O</em>(<em>n</em><sup>2</sup>)<em>, </em>because outer loop need to run from <em>i </em>= 0 to <em>i </em>= <em>n </em>− 2. the inner loop need to run from <em>j </em>= <em>i </em>+ 1<em>toj </em>= <em>n </em>− 1<em>.</em>

(b) (10 points) Give an Θ(<em>n</em>log(<em>n</em>))-time algorithm to do the same task and analyze its running time. (<strong>Hint: </strong>consider sorting relevant events by time). <strong>[We are expecting pseudocode and a brief justification for its runtime.]</strong>

Answer:

Input: List containing the time interval of each users (<em>a</em>1<em>,b</em>1)<em>,</em>(<em>a</em>2<em>,b</em>2)<em>,</em>(<em>a</em>3<em>,b</em>3)<em>,…</em>(<em>an,bn</em>)

<em>A </em>= [<em>a</em>1<em>,a</em>2<em>,a</em>3<em>…an</em>] of n users. (All of the start time) <em>B </em>= [<em>b</em>1<em>,b</em>2<em>,b</em>3<em>..bn</em>] of n users. (All of the end time)

Procedure insert(valueA, root) if (<em>root </em>== <em>null</em>) root= new node(valueA) return if (<em>root.data &gt; valueA</em>) <em>root.left </em>= <em>newnode</em>(<em>valueA</em>) return if(<em>root.data &lt; valueA</em>) if (<em>root.right </em>== <em>null</em>) <em>root.right </em>= <em>newnode</em>(<em>valueA</em>) return insert(<em>valueA,root.right</em>

for <em>i </em>= 0<em>,i &lt; n,i </em>+ + (outer loop) for <em>j </em>= 0<em>,j &lt; n,j </em>+ + (inner loop) if <em>A</em>[<em>bi</em>] <em>&lt;</em>= <em>A</em>[<em>aj</em>]

Output: (<em>i,j</em>)(<em>i </em>+ 1<em>,j</em>)<em>..</em>(<em>n,j</em>) end procedure

First, We put the start time and end time in two different arraysThen, we used the binary search tree to sort the array A with ascending. final, compare the user’s end time with all the start time of the users, when we find the end time is bigger than start time, the left start time have overlap with end time.

Time complexity <em>O</em>(<em>logn</em>) ∗ <em>O</em>(<em>n</em>) = <em>O</em>(<em>logn </em>∗ <em>n</em>), because the big O of binary search tree is <em>O</em>(<em>logn</em>),every time, we need compare the two array n times.