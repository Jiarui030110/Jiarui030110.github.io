---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'Biography'
        education: 'Education'
        interests: 'Interests'
    design:
      # Keep the homepage background plain white.
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: markdown
    id: publications
    content:
      title: '📚 Publications'
      subtitle: ''
      text: |-
       <div class="publication-item">
        <div class="publication-image">
          <img src="/media/publications/Robotic_fish_RAL.png" alt="Robotic_fish_RAL">
        </div>
       <div class="publication-info">
        <div class="publication-title">
         <strong>Online velocity estimation of a robotic fish using artificial lateral line system with velocity-decoupling sensing ability</strong>
        </div>

        <div class="publication-authors">
        <strong>Jiarui He</strong>, Yan zhou, Chengqian Zhang, Huangzhe Dai, Daofan Tang, Chengfeng Pan, Peng zhao
        </div>

        <div class="publication-links">
        [ <a href="https://ieeexplore.ieee.org/document/11130919" target="_blank" rel="noopener">Publication</a> ]
        [ <a href="/uploads/Online_Velocity_Estimation_of_a_Robotic_Fish_Using_Artificial_Lateral_Line_System_With_Velocity-Decoupling_Sensing_Ability.pdf" target="_blank" rel="noopener">PDF</a> ]
        [ <a href="/video/Supporting Video.mp4">Video</a> ]
        </div>
       </div>  
        <div class="publication-year">
          IEEE RAL 2025
        </div>
       </div>
    design:
      columns: '1'

  - block: collection
    id: experience
    content:
      title: Experience
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: honors
    content:
      title: Honors&Awards
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: flase
    design:
      view: citation

  - block: collection
    id: others
    content:
      title: Others
      filters:
        folders:
          - events
    design:
      view: card

---
