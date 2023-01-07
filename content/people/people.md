---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: people

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: lab members
subtitle:

content:
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups:
    - assistant professor
#    - researchers
    - grad students
#    - administration
#    - visitors
    - alumni

design:
  view: masonry
  columns: '2'
  show_interests: false
  show_role: false
  show_social: true
  flip_alt_rows: true
  background: {}
  spacing: {padding: [35px, 0, 35px, 0]}
  background:
    color: "white"
    text_color_light: false
---
