---
layout: post
title: What's with the blog's name?
date: 2023-01-12 00:00:00-0500
description: An explanation of the strange title of this blog
tags: meta math
---

Ah, the Pythagorean theorem, one of the most ubiquitous and useful formulas in all of math. If you have a right triangle with side lengths $$a$$, $$b$$, and $$c$$, they are related by the following formula:

$$
a^2 + b^2 = c^2
$$

If $$a$$, $$b$$, and $$c$$ are all integers, this is known as a "Pythagorean triple". Two examples are the 3-4-5 and 5-12-13 triangles. It's relatively simple to prove that there are an infinite number of these Pythagorean triples, and there are [formulas to produce all of them from the set of positive integers](https://math.stackexchange.com/questions/1386029/are-there-infinitely-many-pythagorean-triples). But what if I change the formula to instead be:

$$
a^n + b^n = c^n
$$

$$
n \geq 3
$$

Are there any integer solutions to this equation?

Enter Pierre de Fermat, a 17th century mathematician specializing in number theory and infintesimal calculus. While reading a copy of _Arithmetica_ by Diophantus, he came across problem II.8, which considers solving the Pythagorean theorem for a known $$c$$. Around 1637, he wrote the following statement in Latin next to the problem:

> Cubum autem in duos cubos, aut quadratoquadratum in duos quadratoquadratos & generaliter nullam in infinitum ultra quadratum potestatem in duos eiusdem nominis fas est dividere cuius rei demonstrationem mirabilem sane detexi. **Hanc marginis exiguitas non caperet.**

or in English:

> It is impossible to separate a cube into two cubes, or a fourth power into two fourth powers, or in general, any power higher than the second, into two like powers. I have discovered a truly marvelous proof of this, which **this margin is too narrow to contain.**

Fermat died in 1665 without ever publishing a proof of the statement (although he did send the problem to his friends as a challenge). After his death, his son published a new version of _Arithmetica_ with Fermat's comments, as well as his proof of the $$a^4 + b^4 = c^4$$ case. However, the cubic version consistently perplexed mathematicians for the next couple hundred years, so much so that the Guiness Book of World Records labeled it the "most difficult mathematical problem"... until the 1980s came around.

In 1986, mathematician Gerhard Frey suggested that proving the modularity theorem (then known as the Taniyama–Shimura-Weil conjecture) would imply Fermat's Last Theorem, and by 1990, Jean-Pierre Serre and Ken Ribet assisted in proving this notion. So then it's simple, right? Just prove the modularity theorem and you have the solution to a 300 year old unsolved problem! The issue is that most mathematicians at the time thought the conjecture would be extremely difficult, if not impossible to prove. One of them was even Ken Ribet.

After learning about the advancements made in Fermat's Last Theorem, Cambridge professor Andrew Wiles began working on a proof of the modularity theorem for semistable elliptic curves, and in turn, Fermat's Last Theorem. After years of hard work, on June 23rd, 1993 Wiles presented his findings in three lectures at the Isaac Newton Institute for Mathematical Sciences in Cambridge. However, there was a problem. During review, referees raised some questions to Wiles that made him realize his proof was actually incomplete. Rumors began to spread about the proof, and there was mounting pressure in the mathematical community for him to release his current work, as it was still useful without proving Fermat's Last Theorem. Wiles spent the next year attempting to fix his proof with one of his former students to no avail.

September 19, 1994 was a Monday morning. Wiles was on the edge of giving up and publishing his current work. Suddenly, he came to a realization, which is best defined in his own words:

> I was sitting at my desk examining the Kolyvagin–Flach method. It wasn't that I believed I could make it work, but I thought that at least I could explain why it didn't work. Suddenly I had this incredible revelation. I realised that, the Kolyvagin–Flach method wasn't working, but it was all I needed to make my original Iwasawa theory work from three years earlier. So out of the ashes of Kolyvagin–Flach seemed to rise the true answer to the problem. It was so indescribably beautiful; it was so simple and so elegant. I couldn't understand how I'd missed it and I just stared at it in disbelief for twenty minutes. Then during the day I walked around the department, and I'd keep coming back to my desk looking to see if it was still there. It was still there. I couldn't contain myself, I was so excited. It was the most important moment of my working life. Nothing I ever do again will mean as much.

The final result was over one hundred pages and almost incomprehensible, except to the highest level mathematicians. The Wikipedia page that has a summary of the proof says "This section needs attention from an expert in mathematics," which is a bit of an understatement. Ribet later stated that he believed Andrew Wiles was one of the only people on Earth that could have created the proof. Although he was too old to win a Fields Medal (the equivalent to a Nobel Prize in Mathematics) for his work, he was knighted, fittingly won the Fermat Prize for the year, and a received a variety of other awards. 

The question that mathematicians are still wondering about now is whether Fermat ever actually had a proof for the cubic case. He probably didn't have working knowledge of the modularity of semistable elliptic curves, as they hadn't really been discovered yet. Perhaps Fermat had created an incorrect demonstration for the $$n = 3$$ case that he was convinced was right, similar to Wiles's original 1993 proof. We'll probably never know what actually happened, but it's certainly fun to think about.

Surprisingly, this isn't the only 300 year old problem solved at the turn of the millenium. University of Pittsburgh's own Thomas Hales announced a proof of the Kepler conjecture, first proposed in 1611, in 1998. However, he used a computer-assisted proof, so it took until 2017 to be formalized and accepted into a journal. If you're one of my students in Big Ideas (CMPINF 0010) this semester, you might even be lucky enough to get a speech from him about computer-assisted proofs and the future of computers in solving difficult mathematical problems.

Now, if you're a budding mathematician yourself and now concerned that all the good problems have been solved already, fear not! The Millenium Problems are a set of seven unsolved mathematical questions with a one-million dollar reward to anyone who can find answers. Only one has been solved so far: the Poincaré conjecture covering the characterization of the 3-sphere (think sphere in 4 dimensions) was proven by Grigori Perelman in 2002. The story of Perelman's proof of the Poincaré conjecture is worth a whole blog post in itself, so I'll just file that away for another time. Until then, keep working hard.

\- Griffin

Sources:
- [https://en.wikipedia.org/wiki/Modularity_theorem](https://en.wikipedia.org/wiki/Modularity_theorem)
- [https://en.wikipedia.org/wiki/Wiles%27s_proof_of_Fermat%27s_Last_Theorem](https://en.wikipedia.org/wiki/Wiles%27s_proof_of_Fermat%27s_Last_Theorem)
- [https://en.wikipedia.org/wiki/Fermat_Prize](https://en.wikipedia.org/wiki/Fermat_Prize)
- [https://en.wikipedia.org/wiki/Andrew_Wiles](https://en.wikipedia.org/wiki/Andrew_Wiles)
- [https://en.wikipedia.org/wiki/Kepler_conjecture](https://en.wikipedia.org/wiki/Kepler_conjecture)
- [https://en.wikipedia.org/wiki/Millennium_Prize_Problems](https://en.wikipedia.org/wiki/Millennium_Prize_Problems)

(Yes, I know Wikipedia is not a scholarly source, but this is just meant to be a fun blog post. Take it with a grain of salt.)