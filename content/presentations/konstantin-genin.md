---
title: Performativity and Prospective Fairness
type: landing

sections:
  - block: markdown
    content:
      title: Performativity and Prospective Fairness
      subtitle: Konstantin Genin <br/> *University of Tübingen*
      text: |
        Deploying an algorithmically informed policy is a significant intervention into the structure of society. As is increasingly acknowledged, predictive algorithms have performative effects: using them can shift the distribution of outcomes away from the one on which the algorithms were trained. Algorithmic fairness research is usually motivated by the worry that these performative effects will exacerbate the structural inequalities reflected in the training data. However, standard retrospective fairness methodologies are ill-suited to account for such performativity. They impose static fairness constraints that hold after the predictive algorithm is trained, but before it is deployed and, therefore, before performative effects have had a chance to kick in. Unfortunately, satisfying static fairness criteria after training is not sufficient to avoid exacerbating inequality after deployment. Our first contribution is conceptual: we argue that addressing the fundamental worry that motivates algorithmic fairness requires a notion of prospective fairness that anticipates the change in relevant structural inequalities after deployment. Our second contribution is methodological: we propose a strategy for estimating this post-deployment change from pre-deployment data. That requires distinguishing between, and accounting for, different kinds of performative effects. In particular, we focus on the way predictions change policy decisions and, therefore, the distribution of outcomes. Throughout, we are guided by an application from public administration: the use of algorithms to (1) predict who among the recently unemployed will remain unemployed in the long term and (2) targeting them with labor market programs. We illustrate our proposal by showing how to predict whether such policies will exacerbate gender inequalities in the labor market.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
