---
title: "On the Impact of Local Differential Privacy on Fairness: A Formal Approach"
type: landing

sections:
  - block: markdown
    content:
      title: "On the Impact of Local Differential Privacy on Fairness: A Formal Approach"
      subtitle: Karima Makhlouf <br/> *Inria and École Polytechnique*
      text: |
        The deployment of machine learning (ML) is growing exponentially in many domains, including those related to various aspects of human and social life. The learning algorithms rely primarily on the availability of training data, and, depending on the domain, these data may include sensitive information about the data providers, thus leading to significant privacy issues. 
        
        Differential privacy (DP) is the predominant solution for privacy-preserving ML. Recent works have shown that DP can impact ML prediction for different subgroups of individuals, thus affecting discriminatory decision-making. However, a formal and systematic understanding of this effect is still lacking. In this work, we formally study the impact of local DP on fairness. Specifically, we perform a  quantitative study of how the accuracy and fairness of the decisions made by the ML model change under the k-ary Randomized Response ($k$-RR) mechanism for different levels of privacy and data distributions.  In particular, we provide bounds in terms of the joint distributions and the privacy level,  delimiting the extent to which local DP can impact the fairness of the model.  In other words, we define the situations under which fairness and accuracy change (increase/decrease) or remain invariant. Our findings show that fairness and privacy can go hand in hand. That is, k-RR can help reduce the disparities between groups and improve fairness. We validate our theoretical findings on synthetic and real-world datasets.

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
