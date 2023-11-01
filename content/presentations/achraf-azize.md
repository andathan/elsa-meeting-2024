---
title: On the Complexity of Differentially Private Best-Arm Identification with Fixed Confidence
type: landing

sections:
  - block: markdown
    content:
      title: On the Complexity of Differentially Private Best-Arm Identification with Fixed Confidence
      subtitle: Achraf Azize <br/> *Inria*
      text: |
        Best Arm Identification (BAI) problems are progressively used for data-sensitive applications, such as designing adaptive clinical trials, tuning hyper-parameters, and conducting user studies to name a few. Motivated by the data privacy concerns invoked by these applications, we study the problem of BAI with fixed confidence under {{< math >}}$\epsilon${{< /math >}}-global Differential Privacy (DP). First, to quantify the privacy-sample complexity *tradeoff*, we derive a lower bound on the sample complexity of any {{< math >}}$\delta${{< /math >}}-correct BAI algorithm satisfying {{< math >}}$\epsilon${{< /math >}}-global DP. Our lower bound suggests the existence of two privacy regimes depending on the privacy budget {{< math >}}$\epsilon${{< /math >}}. In the high-privacy regime (small {{< math >}}$\epsilon${{< /math >}}), the hardness depends on a coupled effect of privacy and a novel information-theoretic quantity, called the Total Variation Characteristic Time. In the low-privacy regime (large {{< math >}}$\epsilon${{< /math >}}), the sample complexity lower bound reduces to the classical non-private lower bound. Second, we propose AdaP-TT, an {{< math >}}$\epsilon${{< /math >}}-global DP variant of the Top Two algorithm. AdaP-TT runs in *arm-dependent adaptive episodes* and adds *Laplace noise* to ensure a good privacy-utility trade-off. We derive an asymptotic upper bound on the sample complexity of AdaP-TT that matches with the lower bound up to multiplicative constants in the high-privacy regime. Finally, we provide an experimental analysis of AdaP-TT that validates our theoretical results.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
