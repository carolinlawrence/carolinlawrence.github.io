---
layout: post
title: "Counterfactual Learning of Semantic Parsers When Even Gold Answers Are Unattainable"
date: 2019-01-14
---
I have written a <a href='https://www.cl.uni-heidelberg.de/statnlpgroup/blog/parsing_when_gold_answers_unattainable/'>blog post</a> on how we can train semantic parsers if neither question-parse nor question-answer pairs can be collected.

# Teaser

In semantic parsing, natural language questions are mapped to semantic parses. A semantic parse can be executed against a database to obtain an answer. This answer can then be presented to a user.

Semantic parsers for question-answering can be employed in virtual personal assistants which are increasingly on the rise in recent years. Because such assistants are desired to help on an increasing number of tasks, we need to explore the best possible options to efficiently and effectively set up a parser for a new domain, to adapt them for specific user needs and to generally ensure that they improve.

However, obtaining labelled data can be challenging. In this post, we first consider the different possible supervision signals that can be used to train a semantic parser. This influences which objectives can be used for training, which we explore in the second part.

<h3><a href='https://www.cl.uni-heidelberg.de/statnlpgroup/blog/parsing_when_gold_answers_unattainable/'>Full story.</a></h3>

