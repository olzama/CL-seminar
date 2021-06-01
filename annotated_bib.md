# (Partially) Annotated Bibliography

### Module 1: History of computational linguistics

[SEP Article on CL](https://plato.stanford.edu/entries/computational-linguistics/)
    
   A great fairly comprehensive summary to start with.
    
[Computational Linguistics: History](https://www.sciencedirect.com/science/article/pii/B0080448542009287). Yorick Wilks, Encyclopedia of Language & Linguistics, 2006. 
    
   Wilks is tracing CL back to the beginnings of machine translation and discusses research questions of CL along the way.

[A Life of Language](https://web.stanford.edu/~mjkay/LifeOfLanguage.pdf). Martin Kay, 1994.
    
    A speech given upon receipt of a Lifetime Achievement Award (from the ACL?).

[Aspects of Linguistic Theory in Firthian Linguistics](https://www.tandfonline.com/doi/pdf/10.1080/00437956.1967.11435497), Olasope O. Oyelaran, Word, 2015
    
   Not directly related to CL but relevant, because it talks about the history of theory of meaning.
    
[A pendulum swung too far](https://journals.linguisticsociety.org/elanguage/lilt/article/download/2581/2581-5320-1-PB.pdf). Church, 2011.    
    
   See Module on Rationalism and Empiricism, but also a good article to read on history of the field.
    
### Module 2: CL today: Research questions

[*Science in Action*](https://d1wqtxts1xzle7.cloudfront.net/32543408/99631234-Science-in-Action-by-B-Latour.pdf?1386907159=&response-content-disposition=inline%3B+filename%3DSCIENCE_IN_ACTION_How_to_follow_scientis.pdf&Expires=1616438283&Signature=DZLTmRuraJCo6WcWMiDiRi00fgNKYt7hZ9eLE73PxV1~tUhlqzGjos5eAT~bQegjCkDX7cshAmj165wDnwA49gmkptcpSnkCrZimUfHbb3CxD3VZZv8-XHvI3RF5XjC1qLpGKr8XkyO~Z-hGgiJp9Fk6A~P-TQ-pHH9NHBjh37SQy3mpJp5bXVxnnjrQMndBGGOP8a4BzPq0SPDQJZxH3pAvom9cINFBoRts8CfRJemei-g-fq4N3-6pMxnFaZY0LTY5j4GWvfx29QCMM~Pc5RA0xg5fYhhar4SJQ71kRtbRTgj-1MFO5cmb2Y3dr2QLDv6CGiFjOTZY-I7N7rhoRg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) by Bruno Latour, 1987.

   A fairly unusual book about science and research questions in general.
    
[Review: Surely You Are Joking, Monsieur Latour!](https://www.jstor.org/stable/689826?casa_token=Q-SKwf5EKvAAAAAA:fcld0DCcDueyDp_Ttfgh_zPBhxYKTa-JCP6RT0Y8-XDGfogRSwOxz7H-43bl7btJxt7SdCSaCsnCn7EvngLObmKWWhfXnyzyn7yFyz0ooME7CwjkjSi8&seq=1), by Olga Amsterdamska, 1990.

[Research Questions in Linguistics](http://217.64.17.124:8080/xmlui/bitstream/handle/123456789/571/Methods_in_Linguistics._Litosse.pdf?sequence=1&isAllowed=y), Jane Sunderland, Ch. 1 of *Research Methods in Linguistics*, ed. Lia Litosseliti, 2010

[Vision: NLG can Help Humanize Data and AI](https://ehudreiter.com/2021/03/17/vision-nlg-can-help-humanise-data-and-ai/). Ehud Reiter, 2021

[Language Tasks and Language Games: On Methodology in Current Natural Language Processing Research](https://arxiv.org/abs/1908.10747). David Schlangen, 2020

   This paper takes an AI-driven perspective on CL. Schlangen argues that many goals of computational linguistics are inherently tied to cognitive science theories---because arguably, the main goals of CL have to do with modeling language processing faculties and reasoning/behavioral issues. The conclusion is that working with linguistic and cognitive science theories more should make the argument in CL research generally more explicit.

Julian — empiricism, tasks, data (slides)

The Body Keeps the Score, Bessel van der Kolk, 2014.
The book’s primary content is on van der Kolk’s approach to trauma healing, which integrates physiological and psychological factors.
In the introduction, van der Kolk describes what he calls the “pharmacological revolution,” which was a sea change in how medical practice (and society) regards and treats mental illness, primarily brought about by the advent of powerful psychiatric drugs. What I found very interesting was how (I think) the advantages and pitfalls of psychiatric drugs and the social and scientific changes they wrought parallel very strongly with those of Deep Learning.


Social Psychology and Science: Lessons from Solomon Asch, Paul Rozin, Personality and Social Psychology Review, 2001.
Presents a methodological critique of social psychology, focusing on its overriding insistence on hypothesis testing and rigorous statistics, which are incongruous with its lack of coherent model systems which would allow statistically rigorous conclusions to generalize. Once again, I feel the parallels to NLP/CL are palpable. Rozin provides a brief diagnosis in terms of status marginality as social psychology exists on the margins of other, more accepted sciences, and suggests more exploratory and qualitative work based on informed intuition. (These comments may also apply to NLP/CL.)


The Generalizability Crisis, Tal Yarkoni, Behavioral and Brain Sciences, 2020 (preprint 2019).
Gives a detailed and thorough account of some of the problems underlying typical statistical technique in the practice of psychology research. These critiques touch both on the pitfalls of the data modeling culture (remarked on by Breiman, and later Norvig — see April 19 refs) and the exaggerated empiricism of psychology research critiqued by Rozin (above).

A Scalable Approach to Reducing Gender Bias in Google Translate, 2020.
This is the latest in a series of blog posts (you can follow links to previous ones) describing Google’s approach to handling gender-ambiguous translation problems. I give this as an example of a way of interrogating the nature of a task to make scientific progress in NLP. (I couldn’t find a proper paper describing the method; not sure if anything beyond these blog posts are published.)


April 19 — Continuation of Apr 12

Julian — philosophical foundations (will add more + notes soon)
On Chomsky and the Two Cultures of Statistical Learning, Peter Norvig, 2011.
Written in response to comments where Chomsky derided CL/NLP/AI for not providing scientific insight, and suggested that much of the work in the field counts either as failure or a “novel” definition of success which cares only about success of a model on held-out data. Norvig provides a defense of this notion of success, and attributes Chomsky’s view essentially to the “data modeling culture” side of Breiman’s “two cultures” of statistical modeling (below), which assumes a simple model of reality and relies on the theorist to choose it correctly, rather than assuming a complex model of reality and challenges the theorist to provide generalizable explanations (...this may not be the best pithy explanation of the differences; just read it directly). He attributes to Chomsky a sort of naive “Platonism” in opposition to his own position, which I would give the name “Behavioralism.” In my view, Norvig’s view inherits from the rejection of the accessibility of metaphysical claims in science that — frankly — underpins much of modern philosophy, including views of the Skeptics, Empiricists (e.g. David Hume), Pragmatists (e.g. William James), and even some Rationalists (at least Kant), as well as philosophers of science (including at least Karl Popper) and, last but not least, Alan Turing in his own arguments (1950) which formed the foundation of AI. 

Statistical Modeling: the Two Cultures, Leo Breiman, Statistical Science, 2001.
Proposes the “two cultures” Norvig references: the data modeling and algorithmic modeling cultures. Data modeling constrains itself to the assumption that the model is correct (e.g., as with linear regression). Breiman critiques the approach as being an obstacle to the use of statistics to solve real problems or model the real world (where the model assumptions are almost always false by a long shot).

Computing Machinery and Intelligence, Alan Turing, Mind, 1950.
Seminal paper which forms part of the philosophical backbone of AI. Turing addresses a philosophical question of the day (Can Machines Think?) by dismissing it as meaningless (basically, metaphysical) and instead insisting on asking questions in the form of testable behaviors. This is where he introduces the Imitation Game, which came to be known as the Turing Test.

The Generalization Crisis
Not to be confused with Yarkoni’s “Generalizability Crisis.”


Behavioralist Critiques of Behavioralism
Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data, Emily M. Bender and Alexander Koller, ACL, 2020.
Argument on the subject of a contemporary debate over language models: can a self-supervised model like GPT-* or BERT be said to “understand” language, or somehow grasp language “meaning”? Argues that this is essentially a category error. The argument itself is extremely brief, but many behavioral claims (both empirically about GPT-2 and theoretically) are made about language models to illustrate the argument (most notably their “Octopus Test”).
To Dissect an Octopus: Making Sense of the Form/Meaning Debate, Julian Michael, 2020.
My synthesis of the Octopus paper (above) and responses to it. Basically I think Bender & Koller’s argument is out of step with the “behavioralist” tradition in AI, which leads to a lot of unproductive disagreements and leads their argument to sound metaphysical and fall on deaf ears. In order to have practical significance, their argument must reckon with (and provide at least partial refutation of) the behavioralist approach. I provide some bones for such an argument in the last section (“Synthesis”) of the post.

Syntactic Structures, Noam Chomsky, 1957.
Chomsky’s famous monograph which formed the foundation of early generative linguistics. Lots could be said about it but I note particularly his criticisms of probabilistic language modeling (referenced by Norvig), where he suggests it is incapable of capturing certain linguistic facts which would be accounted for in formal grammar.

The Shallowness of Google Translate, Douglas Hofstadter, The Atlantic, 2018.
Hofstadter voices doubt about the abilities of MT systems to take on the whole problem of machine translation: through example and argument, he suggests that translation requires situational, social, and psychological understanding which is inaccessible to MT systems as they exist. This closely mirrors the Octopus Paper’s argument, with some of the same shortcomings.

GPT-3, Bloviator: OpenAI’s language generator has no idea what it’s talking about, Gary Marcus and Ernest Davis, MIT Technology Review, 2020.
Yet another example of behavioralist critiques of behavioralism, with many examples of GPT outputs not behaving as the authors expect based on their understanding of the world. However, they also provide a more nuanced argument in the last third of the piece: even if an improv performer often came up with sound medical advice during their performance, you would not go to them for medical advice. You would go to a doctor. I think this point is important; it’s part of what I want to make more precise.
Studies on Syntax


Principles and Abstraction
On the Role of Scientific Thought, Edsger Dijkstra, 1974.
Intelligent Machinery, Alan Turing, 1948.


April 26 — Formal and Statistical Methods
A pendulum swung too far, Church, 2011.
This paper considers the historical oscillations between empiricism and rationalism in CL and AI. In particular, it considers the funding dimension and how funding “winters” are caused by frustration associated with goals which are too long-term, and how focusing on “low-hanging fruit” tends to alleviate such “winters”. At least in the specific cases, there is a correlation here with formal vs. statistical approaches. On the other hand, Church is of the opinion that figures like Chomsky, Pierce, and Misky are directly responsible for the “winters” as well. Talk about the role of personality in history (Tolstoy). That said, Church appears to be a fan of Pierce and emphasizes Pierce’s belief that there should be long-term research in basic disciplines which is not evaluated by industrial/commercial metrics. Throughout the article, Church talks about the debate (between proponents of different methodologies) keeps being lost between generations, and how this could be remedied through teaching. He provides an interesting overview of the modern CL textbooks from this perspective, with many specific examples of the textbooks’ clear failures to mention one side of the argument even when citing works whose main purpose was to put that particular side of the argument forth. He concludes with a couple of examples where richer linguistic representations became more important with time, one of them in MT. Has that changed with deep learning?

On our best behaviour, Levesque, 2013.
A very well-written, entertaining paper arguing for symbolic reasoning in AI. Among other things, it discusses using Winograd Schema questions instead of the Turing test.
Formal and Empirical Methods in Philosophy of Science, Crupi and Hartmann, 2010.
A fairly accessible article from the philosophy of science field. Non-philosophers may need to look up some definitions of course and will inevitably miss some of the content, but it is an interesting exposition of what role empirical and formal methods play in epistemology. The discussion seems relevant to the more general question of how formal and experimental approaches interact in science. In particular, the essay mentions the connection between hypothesis testing in philosophy of science and in cognitive science.

Physics Fight: Theoretical or Experimental? 2019

May 3 — Evaluation
Beyond accuracy. Ribeiro et al., 2020.
ACL 2020 best paper. They put together some test suites and show that state-of-the-art misses most of the checkboxes. Finding and watching the video with slides highly recommended, as it’s very entertaining and follows the grand tradition of Carlos Guestrin’s lectures :).

The ERG at MRP, Oepen and Flickinger, 2019. 
Some evidence that grammars make for better target meaning representations. I put this paper under “evaluation” because this is in the context of discussing meaning representations for evaluation. But it can also be read as part of the “formal vs. statistical methods” section.
What is SemEval evaluating? Wysoki et al., 2020 (or was it ever published?)
This paper is asking, what the contribution of evaluating campaigns actually is? Although it is an overview of various aspects of SemEval rather than a position paper. It concludes that evaluation campaigns may have significant impact on the field and may bias it towards certain methodologies (e.g. deep learning in NLP). Among other things, they suggest separating “competition papers” from research tasks.
AI and the Everything in the Whole Wide World Benchmark, Raji et al., ML Retrospectives, 2020.
A discussion on the history of benchmarking in AI and criticism of the practice of producing “general” benchmarks, or regarding them as “general.” Focuses on the ImageNet Challenge and GLUE benchmark. Julian’s note: while I agree with the general point of the paper, I think some of the criticisms of GLUE are severely lacking context (of course, I think this as an author of GLUE). This was a workshop submission and AFAIK they are continuing to refine the paper. I have corresponded with the authors on a newer draft of the paper. My feedback to them is in this Google doc.
Extrapolating GPT-N Performance, Lukas Finnveden, 2020.
This is an attempt to understand and predict performance trends in AI using benchmarks as a guide. In particular, the author is interested in extrapolating the effect of scale on an AI system’s overall capability. Julian’s note: the most interesting part here IMO is the comment thread in which I had a lengthy discussion with the author. In it I outlined what I believe are a lot of problems that prevent us from drawing conclusions about AI’s usefulness in the real world purely from empirical performance trends on benchmarks, while the author offered their perspective on trying to predict the arrival of “transformative AI.”
A semantic analysis of the English Genitive. 
This was recommended to me on Twitter as illustrating Generative Lexicon. I haven’t yet read it.

May 17 — Academy and Industry
Protections of Tenure and Academic Freedom in the United States. Herzog 2017.
A book (not available online) which talks about the history of tenure in the U.S. and puts forth some discussion on how in the 21st century, the existing system of tenure does not fully protect the professors’ right to speak on controversial topics. The book also contains detailed descriptions of multiple court cases associated with tenure, including Supreme Court cases. While the book is about tenure, it emphasizes that for the most part, issues having to do with the First Amendment apply to untenured faculty just as well as they do to all public employees. According to the book, in court cases where the reason for termination of employment is recognized as potentially having to do with free speech, the courts tend to rule in favor of the professor; however when the reasons for termination are officially financial (e.g. the college’s financial “exigency”), the courts tend to rule in favor of the college. I think the point of the book kind of is that tenure as an institution has nothing to do with protection of academic freedom as established by the courts.

ACL Rolling Review Proposal
In 2020, a suggestion was put forth to reform the ACL reviewing process. The proposal includes a centralized pool of reviewers who can be sent papers at any time (like it happens in journals). Then the already reviewed papers are submitted to conferences. The goals for the reform were stated mainly as making the reviewing process “more systematic” (which I think means, more relevant assignment), reducing time from doing research to publication, increasing quality of papers, and reducing the load of area chairs during conferences. Expressed concerns at the time included diversity of publications (it might decrease even further with the new system).
Revise & Resubmit is damaging to science and should be abandoned, Martin Haspelmath, 2020.
Haspelmath is talking about linguistics journals, and he is arguing that the current situation with the “revise and resubmit” procedure in linguistic journals is unethical and antiscientific in spirit. What he means is: currently in linguistics, a significant proportion of authors submitting to journals get the “revise and resubmit” response. In practice, this means that the author is expected to address the very specific reviewer concerns and show evidence of that when submitting the paper again. The problem with that is that it forces the author to rewrite the paper as the reviewer sees fit. Essentially this makes the reviewer an implicit coauthor. Haspelmath is of the opinion that it is better to just reject papers instead of requesting specific revisions (and then the author can go to another venue to publish their work).  



May 24 — The future!
On the gap between theoretical and computational linguistics. Marco Baroni, EACL 2021 keynote speech.
Linguistic behaviour and the realistic testing of NLP systems. Janet Pierrehumbert. EMNLP 2020 keynote speech.


