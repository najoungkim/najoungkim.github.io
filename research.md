---
layout: default
title: Research
permalink: /research/
---

Here is a topic-by-topic summary of current and past projects I was involved in. Please refer to my <a href="/cv">CV</a> for a chronological list of manuscripts and publications.

* * *

### Gradient blend model of argumenthood
What distinguishes arguments (or complements) from adjuncts? Although people do seem to have intuitions about what counts as an argument, there is no known deterministic test for argumenthood. It has long been suggested that the argument-adjunct status is a spectrum rather than a dichotomy, but how to formally model this gradience has not been actively discussed. I am currently investigating this issue through English preposition phrases, the argument-adjunct status of which is not trivial in many cases. Current projects in this area include:
* Building a gradient argumenthood dataset through crowdsourcing
  * Scaled argumenthood scores for VerbNet and PropBank examples
  * <a href="http://decomp.net/semantic-proto-roles/">Semantic proto-role</a> annotations for preposition phrases
* Developing a linguistic formalism to better capture gradience
  * Advocating the necessity of _blendedness_ in addition to gradience in modeling argumenthood based on human judgment patterns
* Supervised learning of argumenthood

See <a href="/assets/img/organization.png">this diagram</a> from my departmental talk for a better idea of the workflow in this project!

### 'Semantic' scoring of Category Fluency Test results
Category Fluency Test (CFT) is a commonly used behavioral task in clinical settings, as an individual's performance on the task is known to be affected by factors such as age and dementia. The task is to name as many items in a given semantic category (e.g., animals) as possible in a sixty seconds. Traditional analyses of performance on this task mainly rely on word counts, but it has been shown in the literature that 'clustering' and 'switching' patterns in the data also need to be taken into account. However, clustering analysis is not in wide use since it relies on a time-consuming and language/domain-specific manual annotation protocol. Here is a line of work that addresses these issues:

* In this <a target="_blank" href="https://pdfs.semanticscholar.org/9c22/208e82caa1dece8c2f803b16cb89e343d17a.pdf">paper</a> (Interspeech 2016), we have shown that a combination of prosodic and distributional semantic analyses provides important insights into clustering patterns in CFT data. 

* Building on this result, we aim to present a fully automated semantic scoring method using both relational and distributional models (manuscript in preparation). A sketch can be found <a target="_blank" href="http://www.macsim.us/wordpress/wp-content/uploads/2016/09/macsim6_KimN.pdf">here</a> (presented at MACSIM 2016) 

### Morphological strategies in neology
Producing new word-forms through morphology is a part of typical language use, whether or not speakers (or the society) consciously recognize them as novel or not. Inflection (_type-typed_) and derivation (_type-typist_) being example of the most common strategies in English. Native speakers also have an intuition about how productive a strategy is; for instance, _-ness_ seems to be a more productive nominalization affix compared to _-th_. Is this intuition quantifiable, and what can this information tell us?

* In my B.A. dissertation project (2014), I constructed a corpus of Korean _Neograms_, which refers to whitespace units (roughly equivalent to words) that have never been observed before. I developed a novel measure of productivity for an affix and verified it with a human judgment experiment.
  * According to the results, the three most productive Korean affixes (as of 2014) are _-lon 'theory of'_, _-phwung 'style of'_ and _-kyey 'group/type of'_!
* In my Master's dissertation (2015), I developed an automatic detector-classifier for Korean Neograms.
  * Detector uses modified WordRank strategy (_F_=74.08)
  * Classifier can identify the following strategies: compounding, derivation, foreign word/proper nouns and initialism
  * Rule-based; might experiment with a neural model in the future
* A 'lexical innovation' measure (the rate of unobserved words; i.e., Neograms) was developed, taking inspiration from the above works. <a target="_blank" href="http://conference.hcikorea.org/pds/2016/pdf/PR_002.pdf">A longitudinal study</a> (HCI Korea 2016) of literary works by an author diagnosed with Alzheimer's, revealed a strong association between the decline in lexical innovation and the progression of dementia over time. 