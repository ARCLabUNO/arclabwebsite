---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      title: |
        **Advancing Research in Corrections**
      images:
        - filename: image1.jpg
          alt: Image 1 Description
        - filename: image2.jpg
          alt: Image 2 Description
        - filename: image3.jpg
          alt: Image 3 Description
      text: |
        <p style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: white; font-size: 36px; font-weight: bold; text-align: center;">
          Advancing Research to Transform the Future of Corrections
        </p>
    design:
      style: sliding
      background: light
      transition: fade

  - block: hero
    content:
      title: |
        **A**dvancing **R**esearch in **C**orrections
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        <p style="font-size: 16px; line-height: 1.6;">
          The **Advancing Research in Corrections (ARC)** Lab in the [UNO School of Criminology and Criminal Justice](https://www.unomaha.edu/college-of-public-affairs-and-community-service/criminology-and-criminal-justice/index.php) is a collaborative effort dedicated to advancing knowledge and understanding in the fields of institutional corrections, community corrections, and reentry. By leveraging criminological theory alongside rigorous research, assessment, and evaluation, we aim to improve correctional policies, enhance public and institutional safety, and support the successful reintegration of incarcerated individuals into society, ultimately fostering more effective, fair, and transparent correctional systems. 
        </p>

        <p style="font-size: 16px; line-height: 1.6;">
          ARC actively collaborates with SCCJ faculty, Nebraska Center for Justice Research (NCJR) and Juvenile Justice Institute (JJI) staff, community partners, and state and federal agencies to bridge the gap between research and practice. Our partnerships foster a multidisciplinary approach, allowing for the creation of evidence-based solutions that improve both institutional and community outcomes for state and federal departments and individuals involved in the justice system.
        </p>

        <p style="font-size: 16px; line-height: 1.6;">
          Additionally, ARC is committed to providing undergraduate and graduate students with hands-on training in data-driven research, specialized skills essential for understanding corrections and reentry, and valuable networking opportunities that enhance their academic and professional development. By engaging in real-world research and evaluation projects, students are equipped to contribute meaningfully to the field while shaping future policies and practices in institutional and community corrections.
        </p>

        <p style="font-size: 16px; line-height: 1.6;">
          We invite you to explore our website for information on our team, the latest news and information on our current projects, recent publications, and more.
        </p>

  - block: layout
    content:
      left_column:
        text: |
          <h2>Collaborative Research</h2>
          <p>The ARC Lab focuses on research that bridges the gap between corrections theory and practical solutions. By collaborating with stakeholders across various fields, we aim to improve systems of institutional corrections and community reintegration.</p>
      right_column:
        image:
          filename: right_image.jpg
    design:
      columns: '2'
  
  - block: collection
    content:
      title: Latest News
      subtitle: Stay up to date with our latest projects and findings
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---