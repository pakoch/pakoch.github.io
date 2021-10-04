---
title: "Learning compositional sparse bimodal models"
collection: publications
permalink: /publication/2017-compositional
excerpt: 'We model the compositional structure of one domain (speech) in a way that translates to a noncompositional domain (vision) for simple tasks.'
date: 2017-04-12
venue: 'IEEE TPAMI 2017'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/7898500'
citation: 'Kumar, Suren, et al. &quot;Learning compositional sparse bimodal models.&quot; <i>IEEE Transactions on Pattern Analysis and Machine Intelligence 2017</i>. 2017.'
---
Various perceptual domains have underlying compositional semantics that are rarely captured in current models. We suspect this is because directly learning the compositional structure has evaded these models. Yet, the compositional structure of a given domain can be grounded in a separate domain thereby simplifying its learning. To that end, we propose a new approach to modeling bimodal perceptual domains that explicitly relates distinct projections across each modality and then jointly learns a bimodal sparse representation. The resulting model enables compositionality across these distinct projections and hence can generalize to unobserved percepts spanned by this compositional basis. For example, our model can be trained on red triangles and blue squares; yet, implicitly will also have learned red squares and blue triangles. The structure of the projections and hence the compositional basis is learned automatically; no assumption is made on the ordering of the compositional elements in either modality. Although our modeling paradigm is general, we explicitly focus on a tabletop building-blocks setting. To test our model, we have acquired a new bimodal dataset comprising images and spoken utterances of colored shapes (blocks) in the tabletop setting. Our experiments demonstrate the benefits of explicitly leveraging compositionality in both quantitative and human evaluation studies.

[Download paper here](http://pakoch.github.io/pdfs/Kumar_et_al_2017.pdf)

Recommended citation: Kumar, Suren, et al. "Learning compositional sparse bimodal models." <i>IEEE Transactions on Pattern Analysis and Machine Intelligence 2017</i>. 2017.