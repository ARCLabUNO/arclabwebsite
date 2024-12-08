---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        **A**dvancing **R**esearch in **C**orrections
      subtitle: |
        Advancing knowledge in institutional corrections, community corrections, and reentry.
      image:
        filename: welcome.jpg
      cta:
        - label: "Learn More"
          url: "#about" # Add an anchor link or replace with a page URL
          style: primary
        - label: "Latest News"
          url: "#latest-news"
          style: secondary

  - block: markdown
    content:
      title: |
        Welcome to the ARC Lab
      text: |
        The **Advancing Research in Corrections (ARC)** Lab in the [UNO School of Criminology and Criminal Justice](https://www.unomaha.edu/college-of-public-affairs-and-community-service/criminology-and-criminal-justice/index.php) is a collaborative effort dedicated to advancing knowledge and understanding in the fields of institutional corrections, community corrections, and reentry. By leveraging criminological theory alongside rigorous research, assessment, and evaluation, we aim to improve correctional policies, enhance public and institutional safety, and support the successful reintegration of incarcerated individuals into society, ultimately fostering more effective, fair, and transparent correctional systems. 
        
        ARC actively collaborates with SCCJ faculty, Nebraska Center for Justice Research (NCJR) and Juvenile Justice Institute (JJI) staff, community partners, and state and federal agencies to bridge the gap between research and practice. Our partnerships foster a multidisciplinary approach, allowing for the creation of evidence-based solutions that improve both institutional and community outcomes for state and federal departments and individuals involved in the justice system.

        Additionally, ARC is committed to providing undergraduate and graduate students with hands-on training in data-driven research, specialized skills essential for understanding corrections and reentry, and valuable networking opportunities that enhance their academic and professional development. By engaging in real-world research and evaluation projects, students are equipped to contribute meaningfully to the field while shaping future policies and practices in institutional and community corrections.

        We invite you to explore our website for information on our team, the latest news and information on our current projects, recent publications, and more.

  - block: collection
    content:
      title: Latest News
      subtitle: Stay updated with our latest findings and projects.
      text:
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

  - block: slider
    content:
      title: Explore Our Work
      interval: 5000
      height: '400px' # Adjust height as needed
      item:
        - title: "Innovative Research in Corrections"
          content: "Explore our cutting-edge studies and initiatives."
          overlay_img: coders.jpg
          overlay_color: "#00000080" # Semi-transparent overlay for readability
        - title: "Bridging Research and Practice"
          content: "Collaborating with communities and agencies to drive meaningful change."
          overlay_img: another_image.jpg # Replace with actual image
          overlay_color: "#00000080"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---