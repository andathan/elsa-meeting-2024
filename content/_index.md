---
# Leave the homepage title empty to use the site title
title:
type: landing

sections:
  - block: markdown
    content:
      title: |
        <center>{{<figure src="logos-all-white.png" width="50%" height="50%">}}</center>
      subtitle: |
        Workshop @ Comète on Ethical AI
        {style="color: white;font-size: 2.25rem;"}
      text: |
          November 23-24, 2023 - Palaiseau, Paris, France
          {style="color: white;font-size: 1.1rem;text-align: center"}
    design:
      columns: '1'
      background:
        image: 
          filename: ethics.png
          filters:
            brightness: .5
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['2%', '0', '20%', '0']
      # css_class: fullscreen

  - block: markdown
    id: about
    content:
      title: About
      subtitle: 
      text: |
        The research team [Comète (Inria Polytechnique)](https://team.inria.fr/Comete/) is launching a call for proposals for a 2 days workshop on **Ethical Artificial Intelligence**, that will take place on 23th-24th November 2023. For this second session, we focus on the **intrinsic trade-offs** that lie at the heart of Ethical AI. As we observe encouraging progress in domains such as **Fairness, Privacy, Explainability, and Robustness**, we also see tensions between different goals of Ethical AI. The goal of this Workshop is to have a higher-level overview of the challenges and achievements of trying to satisfy multiple desiderata of Ethical AI at once. We seek to bring together researchers from diverse disciplines in computer science, social sciences, law, and industry practitioners. The possible topics include, but are not limited to trade-offs between:
          - Fairness and accuracy
          - Privacy and accuracy
          - Causality in Ethical AI
          - Explainability and accuracy
          - Robustness and accuracy
          - Privacy and fairness
          - Technological progress and following ethical guidelines
          - Technological progress and job loss
          - Cultural values and objectivity
          - Open source and regulation
          - Safety and performance

        Join us for interdisciplinary discussions, thought-provoking conversations, knowledge-sharing, and friendly coffee breaks :). Last but not the least, the workshop is getting famous for French gourmet dinner for the participants!
        
        {{< cta cta_text="Click here to register" cta_link="https://docs.google.com/forms/d/e/1FAIpQLSc8_ifqA8GsnqDTKG8hXoviVBWJvqQ8_-aV2cwUrXmmjWo0jA/viewform?usp=sf_link">}}

        If you have any questions please contact szilvia.lestyan@inria.fr.

        {{% callout note %}}
        #### Key dates
        - Abstract submission: ~~09th October 2023~~ ~~19th October 2023~~
        - Confirmation of acceptance: ~~21th October 2023~~
        - Workshop: 23th-24th November 2023
        {{% /callout %}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: card

  - block: people
    id: keynotes
    content:
      title: Keynote Speakers
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Keynotes
      sort_by: Params.first_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_organizations: true
      view: card        
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card

  - block: markdown
    id: programme
    content:
      title: Programme
      # subtitle: 
      text: |
        <style>
          thead {
            background: rgb(252,213,100);
          }
          tr:nth-child(even) {
            background-color: #f2f2f2;
          }
        </style>
        | **Thursday**   |                                                                    ||
        |----------------|--------------------------------------------------------------------|-|
        | **Time**       | **Event**                                                          ||
        | 10:30 – 12:00  | Welcome Brunch                                                     ||
        | 12:00 – 13:15  | **Keynote: Ljupcho Grozdanovski -- _University of Liège_** <br/> **The Explanations One Needs for the Explanations One Gives: Thoughts on the Epistemic Link between Explainable AI and Causal (Evidentiary) Explanations under the EU’s AI Liability Regulation** | [[Abstract]]({{< relref "authors/ljupcho" >}}) |
        | 13:15 – 13:30  | Short coffee break                                                 ||
        | 13:30 – 13:50  | What is the meaning of "bias" in AI? <br/> *Ambre Davat* -- *GRESEC / Chaire Ethique & IA (Institut MIAI)*    | [[Abstract]]({{< relref "../presentations/ambre-davat" >}})|
        | 13:50 – 14:10  | The need for an interdisciplinary approach to AI research Developing a research ethics framework for AI <br/> *Anais Resseguier* -- *Trilateral Research* | [[Abstract]]({{< relref "../presentations/anais-resseguier" >}})|
        | 14:10 – 14:30  | What ethics does neuroethics bring to bear on the issue of convergence of AI and neurosciences? <br/> *Tabouy Laure* -- *Universite Paris-Saclay, CESP INSERM U1018* | [[Abstract]]({{< relref "../presentations/tabouy-laure" >}})|
        | 14:30 – 14:50  | Dual Use Concerns of Generative AI and Large Language Models <br/> *Laurynas Adomaitis, Alexei Grinbaum* -- *CEA/Saclay* | [[Abstract]]({{< relref "../presentations/laurynas-adomaiti" >}})|
        | 14:50 – 15:15  | **Break**                                                              ||
        | 15:10 – 15:30  | *Karima Makhlouf* | [[Abstract]]({{< relref "../presentations/karima-makhlouf" >}}) |
        | 15:30 – 15:50  | Differential Privacy has Bounded Impact on Fairness in Classification <br/> *Michaël Perrot*  -- *Inria* | [[Abstract]]({{< relref "../presentations/michael-perrot" >}}) |
        | 15:50 – 16:10  | Enhancing Metric Privacy With a Shuffler <br/> *Andreas Athanasiou* -- *PhD Researcher at INRIA,  PhD Student École polytechnique* | [[Abstract]]({{< relref "../presentations/andreas-athanasiou" >}}) |
        | 16:10 – 16:30  | On the Complexity of Differentially Private Best-Arm Identification with Fixed Confidence <br/> *Achraf Azize* -- *Inria* | [[Abstract]]({{< relref "../presentations/achraf-azize" >}}) |
        | 16:30 – 16:45  | **Break**                                                              ||
        | 16:45 – 18:00  | **Keynote: Ferdinando Fioretto -- _University of Virginia_** <br/> **Privacy and Fairness in Societal Systems** | [[Abstract]]({{< relref "authors/fioretto" >}}) |
        | 18:00 - 19:00  | Free time, free discussions, go to restaurant                      ||
        | 19:00 - ?      | Dinner at [Bar 19 (approx 500m walk from INRIA building)](https://maps.app.goo.gl/1EjQ7LiPJ4dPM2ow5)            ||

        | **Friday**     |                                                         ||
        |----------------|---------------------------------------------------------|-|
        | **Time**       | **Event**                                               ||
        | 08:30 – 09:00  | Welcome Coffee                                          ||
        | 09:00 – 09:20  | A Taxonomy of Security Threats, Vulnerabilities, and Controls of AI Systems <br/> *Yusuke Kawamoto* -- *AIST* | [[Abstract]]({{< relref "../presentations/yusuke-kawamoto" >}}) |
        | 09:20 – 09:40  | Legal regulation of AI and morality in the context of natural law and legal positivism <br/> *Arturas Grumulaitis* -- *Vilnius University* | [[Abstract]]({{< relref "../presentations/arturas-grumulaitis" >}}) |
        | 09:40 – 10:00  | When artificial intelligence goes fishing: On the importance of complete and representative training data of AI-driven competition law enforcement <br/> *Jerome De Cooman* -- *University of Liege* | [[Abstract]]({{< relref "../presentations/jerome-cooman" >}}) |
        | 10:00 – 10:20  | *Konstantin Genin* | [[Abstract]]({{< relref "../presentations/konstantin-genin" >}}) |
        | 10:20 – 10:40  | *Martina Cinquini* | [[Abstract]]({{< relref "../presentations/martina-cinquini" >}}) |
        | 10:40 – 11:00  | **Break**                                                   ||
        | 11:00 – 11:20  | How safe are LLMs compared to search engine autocompletions? A bias check-up <br/> *Alina Leidinger* -- *University of Amsterdam* | [[Abstract]]({{< relref "../presentations/alina-leidinger" >}}) |
        | 11:20 – 11:40  | When mitigating bias is unfair: predictive multiplicity in algorithmic fairness <br/> *Thibault Laugel* -- *AXA* | [[Abstract]]({{< relref "../presentations/thibault-laugel" >}}) |
        | 11:40 – 12:00  | Active Fourier Verifier: PAC Estimation of Model Properties with Influence Functions and Fourier Representations <br/> *Ayoub Ajarra* -- *Inria Lille - Scool* | [[Abstract]]({{< relref "../presentations/ayoub-ajarra" >}}) |
        | 12:00 – 12:20  | Leveraging fairness to quantify attribute inference attacks success <br/> *Jan Aalmoes* -- *INSA Lyon* | [[Abstract]]({{< relref "../presentations/jan-aalmoes" >}}) |
        | 12:20 – 12:40  | Mitigating inherent biases in language models by reinforcement learning <br/> *Miguel Couceiro* -- *Université de Lorraine, CNRS, LORIA* | [[Abstract]]({{< relref "../presentations/miguel-couceiro" >}}) |
        | 12:40 – 13:45  | **Lunch**                                                   ||
        | 13:45 – 15:15  | **Keynote: Giada Pistilli -- _Hugging Face_** <br/> **Conversational AI Ethics: Philosophy and Real-World Case Studies** | [[Abstract]]({{< relref "authors/giada" >}}) |
        | 15:15 – 15:30  | **Break**                                                  ||
        | 15:30 – 17:00  | Round Table                                             ||
        | 17:00 – 18:00  | Free discussions with coffee and snacks                 ||
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact

  - block: contact
    id: venue
    content:
      title: Venue
      subtitle:
      text: |
        > Inria Saclay  
        1 Rue Honoré d'Estienne d'Orves  
        Bâtiment Alan Turing  
        Campus de l'École Polytechnique  
        Palaiseau, France
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '48.7145246'
        longitude: '2.2056062'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: people
    id: organizers
    content:
      title: Organizers
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Organizers
      sort_by: Params.first_name
      sort_ascending: false
    design:
      show_interests: false
      show_role: true
      show_social: true
      view: card
---


# <style>
# thead {
#   background-color: rgb(252,205,77,.7);
# }
# # tr:nth-child(even) {
# #   background-color: #b2b2b2!important;
# #   color: #f4f4f4!important;
# # }
# </style>

# | *Monday, October 2*     |
# |-----------------| :---    |
# | 09:00 - 10:00   | A       |
# | 10:00 - 11:00   | B       |
# | 11:00 - 12:00   | C       |
# | 12:00 - 14:00   | Lunch   |

# | *Tuesday, October 3*       |
# |-----------------| :---    |
# | 09:00 - 10:00   | A       |
# | 10:00 - 11:00   | B       |
# | 11:00 - 12:00   | C       |
# | 12:00 - 14:00   | Lunch   |
