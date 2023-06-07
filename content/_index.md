---
# Leave the homepage title empty to use the site title
title:
type: landing

sections:
  - block: markdown
    content:
      title: Workshop @ Comète on Ethical AI
      subtitle: October 5, 2023 - Palaiseau, Paris, France
      text:
    design:
      columns: '1'
      # background:
      #   image: 
      #     filename: coders.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      # css_class: fullscreen

  - block: markdown
    id: about
    content:
      title: About
      subtitle: 
      text: |
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: card
  
  - block: contact
    id: location
    content:
      title: Location
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
      columns: '1'

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      # show_social: true
      view: card

  # - block: hero
  #   content:
  #     title: |
  #       Wowchemy
  #       Research Group
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---