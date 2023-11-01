---
title: Enhancing Metric Privacy With a Shuffler
type: landing

sections:
  - block: markdown
    content:
      title: Enhancing Metric Privacy With a Shuffler
      subtitle: Andreas Athanasiou <br/> *PhD Researcher at INRIA,  PhD Student École polytechnique*
      text: |
        Differential privacy (DP) is one of the most successful frameworks to protect privacy. DP was initially designed in the context of statistical datasets, where we assume the presence of a trusted server that acts as an interface between the data and the data consumers (data analysts). The latter cannot access the data directly but only query it via the server, which is supposed to obfuscate the answer by controlled noise, before reporting it to the analysts. One limitation of this model, nowadays also called the central model of DP, is that the server cannot always be trusted: it may be colluded with an attacker, or just be unable to protect the data from security breaches. For this reason, another model has been proposed, the so called local differential privacy (LDP). In LDP the individual data are obfuscated directly at the end of the data provider, before even being collected. Obviously, LDP offers better privacy and security guarantees than central DP, but it suffers from a reduction of utility, in the sense that, for the same level of DP, the results of analyses on the obfuscated data are less precise.
        
        To improve LDP, in recent years researchers have proposed to combine it with a shuffler, which is supposed to mix the data at the time of collection, thus breaking the link between the individual record and its original owner. The resulting model, called the shuffle model of (local) differential privacy, enhances the privacy of LDP without affecting utility, thus reducing the gap between LDP and central DP w.r.t. the privacy-utility trade-off.
        
        Metric privacy (aka 𝑑-privacy) is a variant of DP that can be applied in domains provided with a notion of distance. Metric privacy is actually a generalization of both central DP and LDP, but it is especially used in the local model, and particularly in location privacy, where it takes the name of geo-indistinguihability. The main difference with respect to LDP is that the level of distinguishability between two objects depends on their distance. In contrast to LDP, Metric privacy allows calibrating the noise so that data points closer to the true one are more likely to be reported.
        
        In this paper, we study how metric privacy (in the local model) can be improved by combining it with a shuffler. More precisely, we consider the combination of the shuffler with two mechanisms, randomized response and geometric, in the context of the sum and average queries. In both cases, we formally derive the relations that express the privacy amplification due to the shuffler, in terms of metric privacy. We then perform experiments to compare their privacy-utility trade-off and also to compare them with those of the standard geometric mechanism for metric privacy in the central model and in the local model.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
