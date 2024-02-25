### Ronak Mistry ###

# Passionate Mechanical Engineer with a strong background in design and quality control, specializing in the optimization of manufacturing processes. With a solid foundation as a mechanical engineering graduate and two years of industry experience, I am driven by a relentless pursuit of excellence in both design and manufacturing.

Power Bus Way Ltd Brampton, ON   
Junior Mechanical Engineer April 2023 – present

• Interpret mechanical design drawings and specifications.
• Use Autodesk Inventor to create and modify design drawings.
• Generate models within 3D workspace.
• Create/modify 2D & 3D drawings.
• Work with 3D scans and point cloud models
• Prepare product layout and approval drawings.
• Ensure standard design and drawing procedures are followed.
• Prepare component manufacturing drawings for production.
• Prepare installation manuals and arrangement drawings.
• Follow projects through manufacturing processes ensuring proper production and assembly of
components.
• Provide manufacturing and assembly input.
• Provide input to the design of product prototypes and final product designs.
• Perform additional duties as required.
• Prepare and interpret conventional and computer-assisted design (CAD) engineering designs, drawings,
and specifications for machines and components, power transmission systems, process piping, heating,
ventilating and air conditioning systems
• Prepare cost and material estimates, project schedules and reports
• Conduct tests and analyses of machines, components, and materials to determine their performance,
strength, response to stress and other characteristics


### Navbar Settings ###
nav_exclude:                                            # The following paths are excluded from navbar
  - pages/tags.html
  - pages/404.html
  - pages/index.md
  - documentation/partials/**   
  - pages/jhanavi.md                        # For Documentation Only
  - pages/eng.md
  

### Author Info ###
author:
  name              : Yash Rathod
  image             : "assets/img/dp.jpg"
#  behance           : your_username
# dribbble          : your_username
  email             : yr@yashraw.me
  linkedin          : yash-raw
#  facebook          : your_username
  github            : yashraw
# gitlab            : your_username
  instagram         : yash.raw
# kaggle            : your_username

#  medium            : your_username
# soundcloud        : your_username
# spotify           : your_username
# stackoverflow     : your_user_id
# tumblr            : your_username.tumblr.com
# twitch            : your_username
#  twitter           : your_username
# vimeo             : your_username
# youtube           : your_channel_name
# keybase           : your_username


### Posts ###
permalink: /blog/:title


### Collections ###
collections:
  projects:
    output: true
    permalink: /projects/:name
  elements:                                             # For Documentation Only
    output: true                                        # For Documentation Only


### Disqus ###
disqus:
  shortname: yashraw                     # Your website Shortname on disqus


### Analytics ###
analytics:
  enabled: false                                       # Set true to enable analytics
  google:
    tracking_id: UA-188414285-1


### Defaults for collections ###
defaults:
  - scope:
      path: ""
      type: "projects"
    values:
      layout: "page"
  - scope:                                              # For Documentation Only
      path: ""                                          # For Documentation Only
      type: "elements"                                  # For Documentation Only
    values:                                             # For Documentation Only
      layout: "element"                                 # For Documentation Only
  - scope:
      path: ""
      type: "posts"
    values:
      comments: true                                   # Set to true to enable disqus comments
  - scope:
      path: "assets/img"
    values:
      image: true

### Exclude from processing ###
exclude:
  - README.md
  - CONTRIBUTING.md
  - LICENSE
  - "*.log"

  
