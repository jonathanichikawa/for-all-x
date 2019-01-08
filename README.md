
[Source](http://jichikawa.net/forall-x-ubc-edition/ "Permalink to forall x: UBC edition — Jonathan Jenkins Ichikawa")

# _forall x: UBC edition_

_forall x: UBC edition_ is an open-access introductory logic textbook. I developed this text, based on [P. D. Magnus's _forall x_][16], in 2017–18, for particular use in PHIL 220: Introduction to Formal Logic at UBC, a course that I have been teaching since 2011. It is produced under a Creative Commons License, and is free for all students and instructors worldwide.

The full book is available for pdf download [here][17]. I plan to make a printed version available as well, although that work is still in progress. If you'd like to modify it and know LaTeX, you can also download the [LaTeX source code][18].

I'm maintaining a list of know errors [here][19].

If you are enrolled in [my PHIL 220 in January 2019][20], this is your course textbook.

Here are a few points of information about the book:

* designed for a 13-week, introductory logic course with no prerequisites
* covers translation, proof systems, and some basic metatheory (soundness and completeness) for sentential and quantified logic, with identity
* covers both trees (analytic tableaux) and Fitch-style natural deduction systems, with its greater emphasis on trees
* emphasis on translation and laying the groundwork for metatheory; a lesser emphasis than some textbooks give on the ('puzzle-solving') details and mechanics of constructing proofs
* conversational style with fun examples; intended to be relatively accessible to the technically anxious
* free for anyone to use or modify

I reproduce the preface to the book below.

* * *

## Preface to the UBC Edition:

This preface outlines my approach to teaching logic, and explains the way this version of _forall x_ differs from Magnus's original. The preface is intended more for instructors than for students.

> If you teach with this or another free book instead, you'll save your students $50,000 over ten years.

I have been teaching logic at the University of British Columbia since 2011; starting in 2017, I decided to prepare this textbook, based on and incorporating much of P. D. Magnus's _forall x_, which has been freely available for use and modification since 2005. Preparing this text had two main advantages for me: it allowed me to tailor the text precisely to my teaching preferences and emphasis, and, because it is available for free, it is saving money for students. (I encourage instructors to take this latter consideration pretty seriously. If you have a hundred students a year, requiring them each to buy a $50 textbook takes $5,000 out of students' pockets each year. If you teach with this or another free book instead, you'll save your students $50,000 over ten years. It can be sort of annoying to switch textbooks if you're used to something already. But is staying the course worth $50,000 of your students' money?)

This text was designed for a one-semester, thirteen-week course with no prerequisites, introducing formal logic. At UBC, the course has quite a mix of students with diverse academic backgrounds. For many it is their first philosophy course. As I teach _Introduction to Formal Logic_, the course has three central aims: (1) to help students think more clearly about arguments and argumentative structure, in a way applicable to informal arguments in philosophy and elsewhere; (2) to provide some familiarity and comfort with formal proof systems, including practice setting out formal proofs with each step justified by a syntactically-defined rule; and (3) to provide the conceptual groundwork for metatheoretical proofs, introducing the ideas of rigorous informal proofs about formal systems, preparing students for possible future courses focusing on metalogic and computability. I try to give those three elements roughly equal focus in my course, and in this book.

The book introduces two different kinds of formal proof systems — analytic tableaux ('trees') and Fitch-style natural deduction. Unlike many logic texts, it puts its greater emphasis on trees. There are two reasons I have found this to be useful. One is that the algorithmic nature of tree proofs means that one can be assured to achieve successful proofs on the basis of patience and careful diligence, as opposed to requiring a difficult-to-quantify (and difficult-to-teach) "flash of insight". The other is that the soundness and completeness theorems for tree methods are simpler and more intuitive than they are for natural deduction systems, and I find it valuable to expose students to proofs of significant metatheoretical results early in their logical studies. I prove soundness and completeness for a sentential logic tree system in the fifth week of the semester. 

![forallxp92][21]

As presented here, the soundness and completeness proofs emphasize contrasting the systems students learn with hypothetical alternative systems that modify the rules in various ways. A rule like this would undermine the soundness of the system, but not its completeness. If we changed the rules in this way, it would still be both sound and complete. Etc. This helps give intuitive substance to these theorems.

I also include a Fitch-style natural deduction system, both for sentential and quantified logic, both because its premise–conclusion form is particularly helpful for thinking about informal arguments, and because it is important to recognize and follow proofs laid out in that kind of format, for example in more advanced philosophical material. While students do learn to do Fitch-style proofs, I emphasize less of that puzzle-solving kind of skill here than in many textbooks.

The book begins with a systematic engagement with sentential logic in conventional ways: translations, sentential connectives, models, truth tables, and both proof systems, including soundness and completeness for the tree system. Students are thereby able to become familiar with all the central metalogical ideas, incorporating relatively simple logical symbolism, before introducing predicates, quantfiiers, and identity. Once we enrich the language, we go through those previous ideas again, using our more complex vocabulary.

The first book I used for teaching was Greg Restall's _Logic_ (McGill–Queen's University Press, 2006), which I used for several years. My approach to teaching logic is heavily informed by that book; its infuence in this text is particularly clear in the discussion of trees. (The natural deduction system I use is rather different from Restall's.)

![forallxp217][22]

In preparing this text, I began with Magnus's original and edited freely. There are sections where Magnus's prose has been retained entirely, and many of the exercises I have taken unchanged from the original. But I have also restructured many things and added quite a bit of new material. Unlike my version, which focuses on sentential logic before introducing predicates and quantification, Magnus's version integrated the discussion of sentential and quantificational systems, e.g. covering translation for both before discussing models and proofs for either. The original also did not include trees or soundness and completeness proofs. The two chapters on trees (5 and 10) and soundness and completeness (6 and 11) were written from scratch; my chapter on identity (12) is also original. The other material in this edition incorporates Magnus's original material, some parts more heavily edited than others. I have slightly modified Magnus's natural deduction rules.

In December 2018 I am releasing the 1.0 version of this text. I've had "beta" versions available online for a couple of years while teaching with them, but the present version represents a relatively stable version.

Many thanks, first and foremost, to P.D. Magnus for providing this wonderful resource under a Creative Commons license, which made it freely available and gave me the right to modify and distribute it under the same licensing agreement. I hope other instructors will also feel free to either teach directly from this version, or to modify it to develop their own. The typesetting for trees is via Clea F. Rees's prooftrees package; thanks to her for making it available.

I'm grateful to the students in my PHIL 220 in the fall semesters of 2017 and 2018 at UBC, who had an in-progress version of this book as their course textbook. They patiently and helpfully found and pointed out mistakes as I wrote them (incentivized, perhaps, by an offer of extra credit); this version has many fewer errors than it otherwise would have had. Thanks also to Cavell Chan and Joey Deeth, who did careful proofreading, and generated many solutions to exercises for the answer key, supported by a UBC Library Open Access Grant in 2018.

[1]: http://jichikawa.net/
[2]: http://jichikawa.net/research/
[3]: http://jichikawa.net/contextualising-knowledge/
[4]: http://jichikawa.net/contextualismhandbook/
[5]: http://jichikawa.net/epistemology-and-rape-culture/
[6]: http://jichikawa.net/teaching/
[7]: http://jichikawa.net/forall-x-ubc-edition/
[8]: http://jichikawa.net/photography/
[9]: http://jichikawa.net/personal/
[10]: http://jichikawa.net/singing/
[11]: http://jichikawa.net/contact/
[12]: http://www.youtube.com/channel/UCoArmRPUSLD2DCf5znwP_-g
[13]: https://twitter.com/jichikawa
[14]: http://www.facebook.com/10100755301541461
[15]: https://www.flickr.com/people/jichikawa/
[16]: https://www.fecundity.com/logic/
[17]: https://philpapers.org/rec/MAGFXU
[18]: http://jichikawa.net/s/forallx-ubc-sourcecode-10.zip
[19]: http://bit.ly/forallx-errors
[20]: http://bit.ly/phil220
[21]: https://static1.squarespace.com/static/555e10cde4b0c3b8337f5e3d/t/5c27f9406d2a73e6a9a28d82/1546123627110/forallxp92
[22]: https://static1.squarespace.com/static/555e10cde4b0c3b8337f5e3d/t/5c27f9fbaa4a995f08a1eff7/1546123787522/forallxp217 
