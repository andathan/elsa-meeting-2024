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
          November, 16-17, 2023 - Palaiseau, Paris, France
          {style="color: white;font-size: 1.1rem;text-align: center"}
    design:
      columns: '1'
      background:
        image: 
          filename: ethics.jpg
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
        An international woorkshop on issues in Ethical Machine Learning with special focus on Privacy and Fairness. The topics range from theoretical work to practical applications and interdisciplinary discussions.
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
