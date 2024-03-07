# Optimal-Binary-Codes
Efficiently building optimal binary codes 

A $(n, M, d)$ code refers to a set of $M$ words of length $n$ with pairwise minimum Hamming distance greater than or equal to $d$.The Hamming distance of two words is defined as the number of positions (or bits) in which the two codewords have different values. Denote by $A(n, d)$ the maximum integer $M$ such that $(n, M, d)$ code exists. It is known that $A(n, d)=A(n+1, d+1)$ and $A(n, 2d-1) = A(n + 1,2d)$, so it is enough to study either odd or even values of $d$.
You can find bounds for $A(n, d)$, where $n\leq 28$, see https://www.win.tue.nl/~aeb/codes/binary-1.html.  
