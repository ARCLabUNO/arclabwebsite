---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: welcome_arc.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      css_class: smaller-image  # Add a custom class to control the height
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title: |
        Welcome to the ARC Lab!
      text: |
        <br>
        
        The **Advancing Research in Corrections (ARC)** Lab in the [UNO School of Criminology and Criminal Justice](https://www.unomaha.edu/college-of-public-affairs-and-community-service/criminology-and-criminal-justice/index.php) is a collaborative effort dedicated to advancing knowledge and understanding in the fields of institutional corrections, community corrections, and reentry. By leveraging criminological theory alongside rigorous research, assessment, and evaluation, we aim to improve correctional policies, enhance public and institutional safety, and support the successful reintegration of incarcerated individuals into society, ultimately fostering more effective, fair, and transparent correctional systems. 

        ARC actively collaborates with SCCJ faculty, [Nebraska Center for Justice Research (NCJR)](https://www.unomaha.edu/college-of-public-affairs-and-community-service/nebraska-center-for-justice-research/index.php) and [Juvenile Justice Institute (JJI)](https://www.unomaha.edu/college-of-public-affairs-and-community-service/juvenile-justice-institute/index.php) staff, community partners, and state and federal agencies to bridge the gap between research and practice. Our partnerships foster a multidisciplinary approach, allowing for the creation of evidence-based solutions that improve both institutional and community outcomes for state and federal departments and individuals in the justice system.

        Additionally, ARC is committed to providing undergraduate and graduate students with hands-on training in data-driven research, specialized skills essential for understanding corrections and reentry, and valuable networking opportunities that enhance their academic and professional development. By engaging in real-world research and evaluation projects, students are equipped to contribute meaningfully to the field while shaping future policies and practices in institutional and community corrections.

        We invite you to explore our website for information on [our team](https://arcorrectionslab.org/people/), the [latest news](https://arcorrectionslab.org/post/) and information on our [current projects](https://arcorrectionslab.org/projects/), [recent publications](https://arcorrectionslab.org/publication/), and more.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '2'

  - block: slider
    content:
      slides:
        - title: 👋 Welcome to ARC
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: pitch_groupphoto.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
#        - title: Lunch & Learn ☕️
#          content: 'Share your knowledge with the group and explore exciting new topics together!'
#          align: left
#          background:
#            image:
#              # Specify an image from `assets/media/`
#              # or delete the image section to remove it
#              filename: jenn_asc2024.jpg
#              filters:
#                brightness: 0.7
#            position: center
#            color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet our team →" %}}
    design:
      columns: '1'
---
