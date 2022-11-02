write a program that determines whether or not an infinite sum converges
incorporate "sigma" and some kind of visual representation

Suppose that 0 <= a<sub>n</sub> <= b<sub>n</sub>

If n=k &Sigma; &#8734; a<sub>n</sub> diverges, then n=k &#931; &#8734; b<sub>n</sub> diverges

If n=k &#931; &#infin; a<sub>n</sub> converges, then n=k &#931; &#873C; b<sub>n</sub> converges.
----------------------------------
**GOAL**: Find the *esential* behavior and use this to bound the sequence (above or below).

Useful to know the relative sizes of expressions (ordered largest to smallest):

>	1. Facotrials (n!)
>	2. Exponsentials with r > 1 (r^n^)
>	3. Powers of n with p > 0 (n^p^)
>	4. Logarithms (ln n)
>	5. Constants
----------------------------------
**Limit comparison test**
 Suppose that a~n~, b~N~ > 0.

* If lim n-> &#931 &#873C a~n~/b~n~ = L > 0 then n=k &#931 &#873C a~n~ and &#931 &#873C b~n~
	both converge or both diverge.
  
* If lim n-> &#873C a~n~/b~n~ = 0 *and*  n=k &#931 &#873C b~n~ converges, then 
	n=k &#931 &#873C a~n~ converges.

* If lim n-> &#873C a~n~/b~n~ = &#873C *and* n=k &#931 &#873C b~n~ diverges,
	the &#931 &#873C a~n~ diverges.

----------------------------------
**Key Idea:** Keep the fastest growing parts, "ignore" the rest of the noise.
