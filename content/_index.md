---
# Leave the homepage title empty to use the site title
title:
type: landing

sections:
  - block: markdown
    content:
      title: Workshop @ Comète on Ethical AI
      subtitle: October 5-6, 2023 - Palaiseau, Paris, France
      text: |
        <center>{{<figure src="logos-all.png" class="">}}</center>
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
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eget ligula eu lectus lobortis condimentum. Aliquam nonummy auctor massa. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla at risus. Quisque purus magna, auctor et, sagittis ac, posuere eu, lectus. Nam mattis, felis ut adipiscing

        Main topics
        -----------
        - Trade-offs
        - Privacy
        - Fairness
        - Causality
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card

  - block: markdown
    id: keynotes
    content:
      title: Keynotes
      # subtitle: 
      text: |
        - Keynote 1
        - Keynote 2
        - ...
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
          background-color: rgb(252,205,77,.7);
        }
        # tr:nth-child(even ) {
        #   background-color: #b2b2b2!important;
        #   color: #f4f4f4!important;
        # }
        </style>

        | *Thursday, October 5*       |
        |-----------------|---------|
        | 09:00 - 10:00   | A |
        | 10:00 - 11:00   | B       |
        | 11:00 - 12:00   | C      |
        | 12:00 - 14:00   | Lunch   |

        | *Friday, October 6*         |
        |-----------------|---------|
        | 09:00 - 10:00   | A |
        | 10:00 - 11:00   | B      |
        | 11:00 - 12:00   | C      |
        | 12:00 - 14:00   | Lunch   |

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
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      view: card
---