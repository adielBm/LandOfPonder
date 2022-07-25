# Introduction to Algorithms and Data Structures [20407]

**About.** The course conveys the basic concepts of Algorithms. It starts with the topic of function growth -- asymptotic growth, concepts such as $O(n)$, known to you through high school CS but not in its rigorous mathematical definition. It continues to various topics, all with the regular university-level mathematical nature. 

**My experience.** The course was amazing. I couldn't imagine that induction could be so useful for proving algorithm correctness. The variety of uses of induction was inconceivable to me: from the correctness of loop-based algorithms to proving properties of trees and many others.

The course imposed another shift of mindset: algorithms are theoretical in nature, and code is a mere implementation of them. Therefore one may describe an algorithm in clear language and mathematical notation, resulting in clarity for the implementator. Such mathematical description further lets a rigorous correctness analysis be conducted.


The assignments were like mind-nuggets. Very fun and challenging, crafting algorithms for many kinds of problems, and even proving mathematical theorems unrelated to algorithms. I remember one such theorem that was given to me in the first exercise: *A natural number* $n$ *is a square number iff it has an odd number of divisors.* This theorem rests in my mind ever since.

I liked the subject of data structures. The results presented were mind-boggling: many problems that seem hard have surprisingly efficient solutions. 

The most prominent example is finding the median of a list of numbers (which may not be sorted). The trivial solution is to sort the array and pick the middle value, which runs in $O(n\lg n)$ time. Yet there is a solution requiring only $O(n)$ time.

Another example is an efficient technique for maintaining a balanced binary tree: a binary tree whose height is approximately $n\lg n$.

**Preliminaries.** The course requires mathematical maturity, especially with the technique of induction. You should know how to derive basic functions, and use lhospital rule "$0/0$" and "$\infty/\infty$". Calculus isn't required, although it could be helpful for a thorough understanding of the abovementioned preliminaries. Probability isn't required as well, as the related concepts do not require further knowledge than what's taught in class. The exam questions related to probability require mere reference to certain results proved in the book (e.g. using a known probabilistic data structure to meet some imposed criteria).

I did the course without calculus 1 and probability and passed it superbly. If you do plan on taking one of them, calculus should be a priority, as calculus 1 and 2 are (mostly) required for probability.

**Personal Note.** This course got me to appreciate the beauty of algorithm design. The elegance of the ideas astonished me. It implanted me with some contempt for coding: why mess with the disgusting nature of code, like  fixing bugs introduced by the nature of a coding language? Why should I mess with things unrelated to the problem at hand?

After the course programming wasn't as fun as before: I understood that much of the work is repetitive. The workflow of every programming project is the same.

I realized that programming isn't going to be the thing I'm going to do for the rest of my life, a totally opposite speculation to the one that drove me into beginning my degree. And I'm grateful!
