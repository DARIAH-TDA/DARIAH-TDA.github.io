---
layout: post
title:  Embedded Humanities - The Use of Distributional Models in the Digital Humanities
categories: meeting activity workshop
---

## Workshop description ##

In recent years, the Digital Humanities have witnessed the steadily growing popularity of models from distributional semantics which can be used to model the meaning of documents and words in large digital text collections. Well-known examples of influential distributional models include Latent Dirichlet Allocation for topic modeling (Blei *et al.* 2012) or Word2vec for estimating word vectors (Mikolov *et al.* 2013). Such distributional models have recently gained much prominence in the fields of Natural Language Processing and, more recently, Deep Representation Learning (Manning 2016). Humanities data is typically sparse and distributional models help scholars obtain smoother estimations of them. Whereas, for instance, words are conventionally encoded as binary ‘one-hot vectors’ in digital text analysis, embedding techniques from distributional semantics allow scholars to obtain dense, yet rich representations of vocabularies. These embedded representations are known to capture all sorts of valuable relationships between data points, although embedding techniques are typically trained using unsupervised objectives and require relatively little parameter tuning from scholars. Inspiring applications of this emergent technology in DH have ranged from more technical work in cultural studies at large (Bamman *et al.* 2014), case studies in literary history (Mimno 2012; Schoech 2017) or valuable DH-oriented web apps, such as ShiCo (Martinez-Ortiz *et al.* 2016). The availability of high-quality implementations in the public domain, in software suites as gensim, word2vec, or mallet etc. has greatly added these methods’ popularity.

In spite of their huge potential for Digital Humanities, multiple aspects of their application still remain untapped. Unsupervised models such as Word2vec, for instance, are notoriously hard to evaluate directly – often researchers have to resort to indirect evaluations in this respect. This poses the question to which extent the output of distributional models should play a decisive role in hermeneutical debates or controversies in the Humanities. With other techniques for Distant Reading, distributional models moreover share the drawback that they typically only yield a *single reading* for a particular corpus so that for example the polysemy of a word isn’t rendered adequately. Interesting progress into representing the complex variability of meaning has been achieved, for example on the level of diachronic word embeddings, where convincing attempts have been made to allow for semantic shifts in an individual word’s meaning (Hamilton *et al.* 2016; Hellrich and Hahn 2016). Likewise, critical studies have revealed how tightly distributional models reproduce cultural biases with respect to gender and race (Bolukbasi *et al.* 2016), which calls for a debate about the ethical aspects of the matter. Likewise, it deserves emphasis how distributional models depend on large datasets and typically yield poor estimates for more restrictive data collections. This might help explain why word embeddings so far have not that many applications in fields like stylometry, that mostly work with relatively small corpora.

## Organization
The DARIAH working group on Text & Data Analytics Working group ([TDA-WG](http://dariah-tda.github.io/)), in collaboration with the scientific community Digital Humanities Flanders ([DHuF](http://dighum.uantwerpen.be/dighum/wog/)) organizes a one-day workshop, collocated with the [2018 DHd conference](https://dig-hum.de/jahrestagung-dhd-2018) in **Cologne on Tuesday, 27 February 2018**. The workshop aims to bring together ca. 20 practitioners from the Digital Humanities to present and discuss recent advances in the field, through 30-minute presentations on focused case studies, including work-in-progress or theoretical contributions. The day will be wrapped up by a gently, introductory tutorial on the application of topic models.

## Keynote
The workshop will start with a keynote lecture by David Bamman (University of California, Berkeley).

## Audience
Additionally, the workshop aims to reach an audience of non-presenting participants who take an active interest in distributional models and who are planning to apply distributional models to their own data in the near future. We aim to bring together a diverse group of both junior and senior stakeholders in this nascent subfield of DH. The goal of the workshop is to identify the state of the art in the field, identify common challenges and share recommendations for a best practice. Special attention will be given to the (both hermeneutic and quantitative) evaluation of distributional models in the context of Humanities research, which remains a challenging issue. The workshop is open to scholars from all backgrounds with an interest in semantic representation learning and encourages submissions that deal with under-researched, resource-scarce and/or historic languages. 

## Sponsors
The workshop is financially powered by:
- The **DARIAH-DE** Cluster "Quantitative Data Analysis", sponsored by the German Federal Ministry of Education and Research (BMBF)
- The scientific community **Digital Humanities Flanders** (DHuF), sponsored by the Research Foundation Flanders ([FWO](http://www.fwo.be/en/)).
- The DARIAH working group on Text & Data Analytics Working group ([TDA-WG](http://dariah-tda.github.io/))

### Organizers ###

**Fotis Jannidis (University of Würzburg, Germany)**

Fotis.jannidis@uni-wuerzburg.de,[www.jannidis.de](http://www.jannidis.de/)

Fotis holds the chair for literary computing in the department of German studies at the University of Würzburg. In the last years, the main focus of his work is the computational analysis of larger collections of literature, especially narrative texts. He is interested in developing new research methods for this new subfield of literary studies, but also in new applications for established methods and also in a better understanding, why successful algorithms in this field work.

**Mike Kestemont (University of Antwerp, Belgium)**

mike.kestemont@uantwerp.be,[www.mike-kestemont.org](http://www.mike-kestemont.org/)

Mike is a tenure track research professor in the department of Literature the University of Antwerp. He specializes in computational text analysis for the Humanities, in particular stylometry or computational stylistics. He has published  on the topic of authorship attribution in various fields, such as Classics or medieval European literature. Mike actively engages in the debate surrounding the Digital Humanities and attempts to merge methods from Artificial Intelligence with traditional scholarship in the Humanities. He recently took up an interest in so-called ‘deep’ representation learning using neural networks.

## Schedule (Tuesday, 27 February 2018)

(Consult the [main conference program](http://dhd2018.uni-koeln.de/wp-content/uploads/DHd2018-Veranstaltungsprogramm.pdf) for the location, which might subject to last-minute changes.)

- *09:00-10:30*:
    * *09:00-09:30*: Introduction by Fotis Jannidis, *Word embeddings and text semantics*
    * *09:30-10:30*: Keynote lecture by David Bamman
- *10:30-11:00*: Coffee break
- *11:00-12:30*: Paper session 1 (chair: Mike Kestemont):
    * *11:00-11:30*: 'Using  Distributional Models in Lexicology and Linguistics' (Marc Kupietz, Peter Fankhauser, Rainer Perkuhn and Cyril Belica)
    * *11:30-12:00*: 'Modelling the Muggles. Applying distributional semantics to the Harry Potter novels by J.K. Rowling' (Mike Kestemont, Vanessa Joosen and Dirk van Hulle)
    * *12:00-12:30*: 'Using word embeddings for digital conceptual history' (Pim Huijnen, Jaap Verheul, Melvin Wevers, Tom Kenter & Joris van Eijnatten)
- *12:30-14:00*: Lunch break
- *14:00-15:30*: Paper session 2 (chair: Steffen Pielström):
    * *14:00-14:30*: Using Word Embeddings to Support Methods of Quantitative Text Analysis (Christof Schöch)
    * *14:30-15:00*: 'What's in a Topic Model? Foundations for quantitative literary methods' (Fabio Ciotti)
    * *15:00-15:30*: TBA
- 15:30-16:00: Coffee break
- 16:00-17:30: Hands-on tutorial on LDA topic modelling via a Graphical User Interface (Steffen Pielström)

### Keynote details
#### The Long Rise of Distributed Representations* (David Bamman, UC Berkeley)

Distributed representations of words -- where a word is represented not by its identity but rather by the distributional properties of the contexts it appears in -- are in many ways responsible for the significant gains in accuracy that many applications in natural language processing have witnessed over the past five years, and have driven many interesting applications in the computational humanities.  While widespread interest in such representations took off in 2013 with the release of word2vec (Mikolov 2013), distributed representations have a much longer history, arising out of an appreciation of context advocated not only by Wittgenstein, Harris and Firth but also by a millenium of lexicographers and concordance-makers; computational models explicitly including distributed representations have been informing research in NLP and information retrieval for the past thirty years.      

In this talk, I'll outline the history of distributed representations of words to their height today, and unpack what's new about contemporary (neural) methods of learning such representations compared to previous approaches (including what's the same).  By focusing on the fundamentals of representation learning, I'll also discuss how we can incorporate other forms of extra-linguistic information into the representation for a word (such as time, geographical location, or author identity) and use that more complex representation for linguistic reasoning as well.


### Tutorial description

Using LDA (Latent Dirichlet Allocation) for analyzing the content structure of digital text collections is a possibility, that aroused the interest of many digital humanists in the recent years. With the aim of lowering the threshold to try out LDA, we developed the DARIAH TopicsExplorer, a standalone GUI tool based on the DARIAH Topics
library that allows to perform simple LDA topic modeling work flows without writing a single line of code. The aim of the hands-on session will be to demonstrate the current
functionalities of the TopicsExplorer and give participants the possibility to make their first direct experiences with LDA topic modeling. Participants will be instructed to do their own first analyses on both example data and their own text collections.


### Literature ###

**Bamman,D., Underwood, T., Smith, N. A.** (2014):„A Bayesian Mixed Effects Model of Literary Character“, in*Proceedingsof ACL*.

**Blei,David** (2012):„Probabilistic Topic Models“, in *Communications of the ACM* 55, 77-84.

**Bolukbasi,T., Chang, K. W., Zou, J., Saligrama, V., Kalai, A.** (2016): „Quantifying and Reducing Stereotypes in Word Embeddings“,in *arXiv:1606.06121*.

**Chang,J., Gerrish, S., Sang,C., Boyd-Graber, J. L., Blei, D. M.** (2009):„Reading Tea Leaves: How Humans Interpret Topic Models“, in Proceedings of NIPS, 288-296.

**Hamilton,W. L., Leskovec, J., Jurafsky, D.** (2016): „Diachronic Word Embeddings Reveal Statistical Laws ofSemantic Change“, in *Proceedingsof ACL*.

**Hellrich, J., Hahn, U.** (2016): "Measuring the dynamics of lexico-semantic change since the German Romantic period." In Digital Humanities 2016—Conference Abstracts of the 2016 Conference of the Alliance of Digital Humanities Organizations (ADHO).‘Digital Identities: The Past and the Future’. Kraków, Poland (pp. 545-547).

**Manning, Christopher D.** (2016): „Computational Linguistics and Deep Learning“, in *Computational Linguistics* 41,701-707.

**Martinez-Ortiz,C., Huijnen, P., Kenter, T., Verheul, J., Wevers, M., van Eijnatten,J.** (2016): „ShiCo: A Visualization Tool for Shifting Concepts ThroughTime“, in *DigitalHumanities Benelux: Book af Abstracts*, s.p.

**Mikolov,T., Sutskever, I., Chen, K., Corrado, G. S., Dean, J.** (2013): „Distributed representations of words and phrases and their compositionality“, in *Proceedings of NIPS 2013*.

**Mimno, D.** (2012): „Computational Historiography: Data Mining in a Century ofClassics Journals“, in *ACM Journal of Computing in Cultural Heritage*5.

**Schoech, C.** (2017): „Topic Modeling Genre: An Exploration of French Classical andEnlightenment Drama“, *DigitalHumanities Quarterly* 11, s.p.
