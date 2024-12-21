java c
Faculty of Arts  Science
Fall 2024 Quiz 9 - V2
CSC 110 Y1F
Question   1.    Multiple   Choice   Questions         [4   marks]   Part   (a)         [1   mark]
def   f1(numbers: list[int])   ->   None:
for i   in   range(len(numbers)):
numbers[i] =   i   **   2
for j   in range(len(numbers)):
print(j)
Which   of the   following   is   an   appropriate   exact   step   count   for   the   total   steps   the   above   function   takes   (letting   n   be   len(numbers))?
(a)      n   · n            (b)      n +   n      (c)      n +   n2
(d)      n   + 2n(n+1)
Part   (b)         [2   marks]
def   f2(numbers: list[int])   ->   None:
for   i   in   range(10):
numbers.append(i)
for j   in range(len(numbers)):
print(j)
Which   of the   following   is   an   appropriate   exact   step   count   for   the   total   steps   the   above   function   takes   (letting   n   be   len(numbers)   when   f2   is   called)?(a)    n *   10 +   10   *   1   (b)    n * n + 10 *   1         (c)    n * 10
(d)    None   of these   options   Part   (c)         [1   mark]
def   f3(numbers: list[int])   ->   None:
squares   =   [x   **   2 for   x   in   numbers]
for i   in   range(len(squares)):
print(i)
Which   of the   following   is   an   appropriate,   ﬁnal   exact   step   count   for   the   total   steps   the   above   function   takes   in   terms   of input   size   (letting   n be   len(numbers)   when 代 写CSC 110 Y1F Fall 2024 Quiz 9 - V2SQL
代做程序编程语言  f3   is   called)?
(a)      n   · n            (b)      n +   n      (c)      n +   n2
(d)      n   + 2n(n+1)
Question   2.    Runtime   analysis         [5   marks]
Analyse   the   running   time   of the   following   function,   in   terms   of its   input   length,   using   the   same   structure   we   did   in   lecture.
You   should   clearly   state   how   many   steps   each   line   of code   takes.    For   each   loop   in   the   function,   include   the   number   of iterations,   and   number   of steps   per   iteration.Lastly,   provide   the   total   steps   as   an   exact   step   count   (e.g.,   n2   +2n +4)   and   then   a   Theta   expression   (e.g.,   Θ(n2   ))   (note:   you   do   not   need   to   provide   any   formal   proof or justiﬁcation   for   translating   the   exact   count   to   its   associated   Theta   expression,   similar   to   what   we   did   in   lecture).
def   f4(n:   int)   ->   int:
i   =   1
sum   =   0
while   i   < n:
sum   =   sum   +   i
i   =   i   *   2
return   sum
Question   3.      [4   marks]
Consider   the   following   statement:
’a, b   ∈   R+   ,      a   ≤ b   ∆   na   + nb      ∈   O(nb)
a.   Rewrite   the   above   statement,   but   with   the   deﬁnition   of Big   O   expanded.
b.   Prove   the   above   statement   without   using   any   additional   theorems   about   Big   O.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
