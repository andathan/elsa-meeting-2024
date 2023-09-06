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
          - Explainability and accuracy
          - Robustness and accuracy
          - Privacy and fairness
          - Technological progress and following ethical guidelines
          - Technological progress and job loss
          - Cultural values and objectivity
          - Open source and regulation
          - Safety and performance

        Join us for interdisciplinary discussions, thought-provoking conversations, knowledge-sharing, and friendly coffee breaks :). Last but not the least, the workshop is getting famous for French gourmet dinner for the participants!
        
        {{< cta cta_text="Click here to register to attend and/or submit an abstract before 20th September" cta_link="https://docs.google.com/forms/d/e/1FAIpQLSc8_ifqA8GsnqDTKG8hXoviVBWJvqQ8_-aV2cwUrXmmjWo0jA/viewform?usp=sf_link">}}

        If you have any questions please contact szilvia.lestyan@inria.fr.

        {{% callout note %}}
        #### Key dates
        - Abstract submission: 09th October, 2023
        - Confirmation of acceptance: 16th October, 2023
        - Workshop: 23th-24th November, 2023
        {{% /callout %}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: card

  - block: markdown
    id: keynotes
    content:
      title: Keynotes
      # subtitle: 
      text: |
        To be announced.
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
        To be announced.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
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
