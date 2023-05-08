Download Link: https://assignmentchef.com/product/solved-prolog-assignment1-simple-list-processing-and-arithmetic
<br>



<u>Write PROLOG programs:</u>

<ol>

 <li>To determine whether the first two elements of a list are same.</li>

 <li>To determine whether a list is not a two-element list.</li>

 <li>To determine whether two lists are of same length.</li>

 <li>To determine length of a list using your own number system, that does not contain more than two symbols.</li>

 <li>To determine whether two lists are of same length using the length predicate developed in 4 (previous problem).</li>

 <li>To find the last element of a list.</li>

 <li>To find whether an element is a member of a list.</li>

 <li>To find whether two elements are next to each other in a list.</li>

 <li>To append two lists in a third list.</li>

 <li>To find the last element of a list using append predicate developed in 9.</li>

 <li>To find whether an element is a member of a list using append predicate developed in 9.</li>

 <li>To find whether two elements are next to each other in a list using append predicate developed in 9.</li>

 <li>To reverse a list in another list.</li>

 <li>To determine whether a list is a palindrome.</li>

</ol>

[the structure of predicate:

palindrome(L)].

<ol start="15">

 <li>To find the last but one element of a list.</li>

</ol>




<ol start="16">

 <li>To find the K’th element of a list. The first element in the list is number 1.</li>

</ol>

Example:

?- element_at(X,[a,b,c,d,e],3).

{X = c}

<ol start="17">

 <li>To find the sum of all elements of a list.</li>

 <li>To find the length of a list.</li>

 <li>To find the average of all elements of a list using sum and length defined in Problem 17 and 18.</li>

 <li>To find the maximum number from a list.</li>

 <li>To find gcd of two integers.</li>

 <li>To determine whether a given integer number is prime.</li>

</ol>

[Example:

?- is_prime(7). true]




<ol start="23">

 <li>To determine whether two positive integer numbers are coprime.</li>

</ol>

[Two numbers are coprime if their greatest common divisor equals 1.

Example:

?- coprime(35, 64).

true]




<ol start="24">

 <li>To determine the prime factors of a given positive integer. [Construct a flat list containing the prime factors in ascending order.</li>

</ol>

Example:

?- prime_factors(315, L).

{L = [3,3,5,7]}

]




<ol start="25">

 <li>Goldbach’s conjecture.</li>

</ol>

Goldbach’s conjecture says that every positive even number greater than 2 is the sum of two prime numbers. Example: 28 = 5 + 23. It is one of the most famous facts in number theory that has not been proved to be correct in the general case. It has been <em>numerically</em> confirmed up to very large numbers (much larger than we can go with our Prolog system). Write a predicate to find the two prime numbers that sum up to a given even integer.

[Example:

?- goldbach(28, L).

{L = [5,23]}




<ol start="26">

 <li>To generate all integers between two integers N1 and N2, both N1 and N2 included and N2&gt;N1.</li>

</ol>




<ol start="27">

 <li>To count numbers greater than 100.0 in a list.</li>

</ol>




<ol start="28">

 <li>To split a list of numbers in two lists such that one contains negative numbers and other contains positive numbers.</li>

</ol>




<ol start="29">

 <li>To find N!</li>

</ol>




<ol start="30">

 <li>To generate first N Fibonacci numbers.</li>

</ol>








