---
title: "When mitigating bias is unfair: predictive multiplicity in algorithmic fairness"
type: landing

sections:
  - block: markdown
    content:
      title: "When mitigating bias is unfair: predictive multiplicity in algorithmic fairness"
      subtitle: Thibault Laugel <br/> *AXA*
      text: |
        Although thoroughly questioned for largely ignoring any social context, most works in the algorithmic fairness community heavily focus on designing new techniques to find the best possible compromise between a given group fairness objective and predictive accuracy. 
        
        These questions, and their associated risks, are further exacerbated by the opaque aspect of group bias mitigation. Besides the resulting fair, Pareto efficient, model often being a black box, more generally the bias mitigation process itself, i.e. the process of taking into account fairness and replacing a biased model with a new, fair, model, is indeed not transparent. As a result, the practice of enforcing algorithmic fairness for a given real-world application is generally a completely intractable process and its impacts remain unobserved and misunderstood. In this presentation, we aim to formulate a new argument against the blind optimization of group fairness metrics through the lens of model multiplicity, i.e. the fact that multiple models can be learned on the same data and achieve similar predictive performance despite being very different.
        
        By showing the prevalence of this issue and discussing its potential harmful consequences, we argue that independently of the context, setting for any group fairness metrics will generally lead to some notion of arbitrariness. We then derive new criteria to help characterize and better understand the debiasing process and its impacts, and thus mitigate this inherent arbitrariness, hence unfairness.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
