---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # First Section: Hero Image with Text Overlay
  - block: hero
    weight: 1
    content:
      title: |
        **A**dvancing **R**esearch in **C**orrections
      image:
        filename: coders.jpg
        alt: "Welcome Image"
      overlay:
        color: rgba(0, 0, 0, 0.5)  # Semi-transparent black overlay
        text: |
          <h2>Empowering research to improve correctional systems and reintegration.</h2>
          <p>Collaborating across disciplines to create effective, evidence-based solutions.</p>

  # Second Section: About Us
  - block: markdown
    weight: 2
    content:
      title: |
        Welcome to the ARC Lab
      text: |
        <br>
        The **Advancing Research in Corrections (ARC)** Lab in the [UNO School of Criminology and Criminal Justice](https://www.unomaha.edu/college-of-public-affairs-and-community-service/criminology-and-criminal-justice/index.php) is a collaborative effort dedicated to advancing knowledge and understanding in the fields of institutional corrections, community corrections, and reentry. By leveraging criminological theory alongside rigorous research, assessment, and evaluation, we aim to improve correctional policies, enhance public and institutional safety, and support the successful reintegration of incarcerated individuals into society, ultimately fostering more effective, fair, and transparent correctional systems. 

        ARC actively collaborates with SCCJ faculty, Nebraska Center for Justice Research (NCJR) and Juvenile Justice Institute (JJI) staff, community partners, and state and federal agencies to bridge the gap between research and practice. Our partnerships foster a multidisciplinary approach, allowing for the creation of evidence-based solutions that improve both institutional and community outcomes for state and federal departments and individuals involved in the justice system.

        Additionally, ARC is committed to providing undergraduate and graduate students with hands-on training in data-driven research, specialized skills essential for understanding corrections and reentry, and valuable networking opportunities that enhance their academic and professional development. By engaging in real-world research and evaluation projects, students are equipped to contribute meaningfully to the field while shaping future policies and practices in institutional and community corrections.

        We invite you to explore our website for information on our team, the latest news and information on our current projects, recent publications, and more.

  # Third Section: Latest News
  - block: collection
    weight: 3
    content:
      title: Latest News
      subtitle: ""
      count: 5
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
      columns: '1'

  # Fourth Section: Image Slider
  - block: slider
    weight: 4
    content:
      interval: 5000  # Interval for slide transition (in milliseconds)
      height: '500px'
      active: true
      item:
        - title: "Slide 1"
          align: center
          overlay_color: '#000000'
          overlay_img: "coders.jpg"  # Replace with your actual image paths
        - title: "Slide 2"
          align: center
          overlay_color: '#000000'
          overlay_img: "contact.jpg"
        - title: "Slide 3"
          align: center
          overlay_color: '#000000'
          overlay_img: "jenn_asc2024.jpg"
  
  # Fifth Section: Meet the Team Call-to-Action
  - block: markdown
    weight: 5
    content:
      title: ""
      subtitle: ""
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
