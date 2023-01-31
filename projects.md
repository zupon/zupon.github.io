[Home](index.md) | [About Me](aboutme.md) | [CV](cv.md) | [Education](education.md) | [Employment](employment.md) | [Projects](projects.md) | [Contact](contact.md)

# Projects

***

## Automatic Correction of Syntactic Dependency Annotation Differences
##### Presented at LREC conference in June 02022

Read it [here](https://aclanthology.org/2022.lrec-1.769/)!

Annotation inconsistencies between data sets can cause problems for low-resource NLP, where noisy or inconsistent data cannot be easily replaced. We propose a method for automatically detecting annotation mismatches between dependency parsing corpora, along with three related methods for automatically converting the mismatches. All three methods rely on comparing unseen examples in a new corpus with similar examples in an existing corpus. These three methods include a simple lexical replacement using the most frequent tag of the example in the existing corpus, a GloVe embedding-based replacement that considers related examples, and a BERT-based replacement that uses contextualized embeddings to provide examples fine-tuned to our data. We evaluate these conversions by retraining two dependency parsers—Stanza and Parsing as Tagging (PaT)—on the converted and unconverted data. We find that applying our conversions yields significantly better performance in many cases. Some differences observed between the two parsers are observed. Stanza has a more complex architecture with a quadratic algorithm, taking longer to train, but it can generalize from less data. The PaT parser has a simpler architecture with a linear algorithm, speeding up training but requiring more training data to reach comparable or better performance.

## Text Normalization for Low-Resource Languages of Africa
##### Presented at AfricaNLP workshop in April 02021.

Read it [here](https://arxiv.org/pdf/2103.15845.pdf)!

Training data for machine learning models can come from many different sources, which can be of dubious quality. For resource-rich languages like English, there is a lot of data available, so we can afford to throw out the dubious data. For low-resource languages where there is much less data available, we can’t necessarily afford to throw out the dubious data, in case we end up with a training set which is too small to train a model. In this study, we examine the effects of text normalization and data set quality for a set of low-resource languages of Africa---Afrikaans, Amharic, Hausa, Igbo, Malagasy, Somali, Swahili, and Zulu. We describe our text normalizer which we built in the Pynini framework, a Python library for finite state transducers, and our experiments in training language models for African languages using the Natural Language Toolkit (NLTK), an open-source Python library for NLP.

## An Analysis of Capsule Networks for Part of Speech Tagging in High- and Low-resource Scenarios

Read it [here](https://zupon.github.io/files/zupon_capsnet.pdf)!

Neural networks are a common tool in NLP, but it is not always clear which architecture to use for a given task. Different tasks, different languages, and different training conditions can all affect how a neural network will perform. Capsule Networks (CapsNets) are a relatively new architecture in NLP. Due to their novelty, CapsNets are being used more and more in NLP tasks. However, their usefulness is still mostly untested. In this paper, we compare three neural network architectures—LSTM, CNN, and CapsNet—on a part of speech tagging task. We compare these architectures in both high- and low-resource training conditions and find that no architecture consistently performs the best. Our analysis shows that our CapsNet performs nearly as well as a more complex LSTM under certain training conditions, but not others, and that our CapsNet almost always outperforms our CNN. We also find that our CapsNet implementation shows faster prediction times than the LSTM for Scottish Gaelic but not for Spanish, highlighting the effect that the choice of languages can have on the models.

## A Corpus Analysis of Breton Soft-Mutation Irregularities
##### Presented at Typologi ar Brezhoneg (Typology of Breton) conference in June 02018.

Traditional Breton grammars state where the soft mutation should and should not occur (Hemon 1995). Using an online Breton corpus (Eckart and Quasthoff 2013), we investigate how often the soft mutation actually surfaces. We focus on the mutation triggers ‘da’, ‘daou’, ‘div’, ‘holl’, ‘pa’, ‘pe’, and ‘re’, which should always trigger the soft mutation, and on mutation targets beginning with \<m>, \<p>, \<t>, \<k>, and \<gw>, which should all undergo the soft mutation. We also look at \<d>-initial targets after definite and indefinite articles. We find variation across the board, with \<p> in particular standing out.

Three patterns emerge from our study. First, all triggers fail to cause mutation some of the time. ‘pe’ causes mutation less frequently than the others. Second, the frequency of mutation varies with the initial consonant of the target. \<p>-initial targets mutate the least. Finally, we observe \<d>-initial targets mutating to \<z> after articles, where \<d> is prescriptively immune to mutation. These findings show that the prescriptive rules for the soft mutation are not rigidly followed; some triggers fail to cause mutation, and some immune targets nevertheless undergo mutation. A similar phenomenon is observed in Scottish Gaelic (Hammond et al. 2017).


## Scottish Gaelic Part-of-Speech tagger

Read it [here](https://zupon.github.io/files/zupon_taggingSG.pdf)!

As a final project for Mihai Surdeanu's Statistical NLP course I developed a part-of-speech tagger for Scottish Gaelic, a low-resource language. My implementation achieves over 80% accuracy on overall tags and over 22% accuracy on unknown words using an LSTM neural network. Prior work by Lamb and Danso (2014) only achieves 76.6% accuracy on the same dataset, using a Brill bigram tagger.

A link to the full project is forthcoming.


## Icelandic Quirky Agreement Restrictions (MA Thesis)

Read it [here](https://zupon.github.io/files/zupon_ma_thesis.pdf)!

This thesis proposes a novel defective T analysis for explaining two facts about Icelandic quirky subject sentences. First, in Icelandic quirky subject sentences, the verb agrees with the nominative object rather than with the subject. Second, 1st and 2nd person nominative objects are blocked completely in Icelandic quirky subject sentences.

Based in a Minimalist Program framework, I argue that T in quirky subject sentences is phi-defective, lacking \[Person\]. I also describe three potential alternative Minimalist analyses of Icelandic: (i) a phi-stacking analysis based on Richards’ case-stacking; (ii) a complex dependency analysis from López; and (iii) a split phi probe analysis supported by Sigurðsson and Holmberg. All of these alternatives come with additional theoretical baggage that makes them suboptimal for explaining the quirky Icelandic facts. I also show how previous analyses of Icelandic all fail to adequately explain the data.


## Restrictions on Denominal Verb Formation (BA Thesis)

Read it [here](https://zupon.github.io/files/zupon_ba_thesis.pdf)!

Why can one say _shelve the books_ but not _desk the papers_? Only certain noun roots typically become denominal verbs. In this thesis I analyze the distribution of denominal verbs in English and restrictions on their formation. I argue that denominal verbs have an additional pragmatic component which is broadly tied to manner, encyclopedic knowledge, or real world typicalities. Shelving books has different connotations than simply putting books on a shelf, whereas there is no equivalent secondary meaning relating to placing objects on a desk. There are two sides to this analysis. The first is that the restrictions on denominal verb formation are an effect of the process itself. In this view, any noun root could undergo this process, but the derived denominal verb will be licit only if extra meaning is associated with the action. This analysis rests in formal pragmatics. The second analysis is that this additional meaning component is a part of the noun root itself, and the presence of such a component becomes realized in the formation of denominal verbs. The presence of this component on individual noun roots can be argued from lexically-similar pairs of words such as _can/jar_, where only one undergoes the denominal verb formation process.
