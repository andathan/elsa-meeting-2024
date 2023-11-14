---
title: Leveraging fairness to quantify attribute inference attacks success
type: landing

sections:
  - block: markdown
    content:
      title: Leveraging fairness to quantify attribute inference attacks success
      subtitle: Jan Aalmoes <br/> *INSA Lyon*
      text: |
        Machine learning (ML) models have been deployed for high-stakes applications, e.g., healthcare and criminal justice. 
        Privacy and fairness are two important aspects to trust ML models for decision making in such applications.
        Prior work has focused on the assessment of privacy risk through through the prism of Membership Inference Attacks (MIAs) which infer data used to train the target model. However, ML models are also vulnerable to blackbox attribute inference attacks (AIAs) where an adversary, with some background knowledge, infers sensitive attributes by exploiting distinguishable model predictions. 
        In this work, we theoretically show that the success of any AIA is bounded by the fairness level of the targeted model. Specifically, the more a model is close to satisfying demographic parity, the less any AIA will perform. 
        Therefore,  the privacy risk of a model can be assessed by simply studying its fairness.
        We also validated empirically our theory through an new AIA which takes advantage of the finite character of the classified set on a large set of representative and real world dataset in various domains such as justice, healthcare, and facial recognition.
        We show that our new AIA provides the upper bound of the balance accuracy of the attack, and that current state of libraries such as Fairlearn (i.e., implementing Exponent Gradient Descent and Adversarial Debasing) and FairGrad failed to guarantee fairness in practice.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
