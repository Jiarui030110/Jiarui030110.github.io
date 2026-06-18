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
        text: My Detailed CV
        url: /uploads/Jiarui_He_CV.pdf
      headings:
        about: 'About'
        #education: 'Education'                                             
        #interests: 'Interests'
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
          <img src="/media/publications/Magnetic cilia for flow measurement.png" alt="Magnetic cilia for flow measurement">
        </div>
       <div class="publication-info">
        <div class="publication-title">
         <strong>Biomimetic magnetic cilia sensor for flow vector measurement and motion state estimation of aquatic objects</strong>
        </div>

        <div class="publication-authors">
        <strong>Jiarui He</strong>, Huangzhe Dai, Kan Liu, Chengfeng Pan, Neng Xia, Chengqian Zhang, Peng zhao
        </div>

        <div class="publication-year">
         Submitted to IEEE Transactions on Instrumentation and Measurement (TIM), Under Review, May.2026.
        </div>
       </div>  
       </div>

      
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

        <div class="publication-year">
          IEEE Robotics and Automation Letters (RA-L), Aug.2025.
        </div>

        <div class="publication-links">
        [ <a href="https://ieeexplore.ieee.org/document/11130919" target="_blank" rel="noopener">Publication</a> ]
        [ <a href="/uploads/Online_Velocity_Estimation_of_a_Robotic_Fish_Using_Artificial_Lateral_Line_System_With_Velocity-Decoupling_Sensing_Ability.pdf" target="_blank" rel="noopener">PDF</a> ]
        [ <a href="/video/Supporting Video.mp4">Video</a> ]
        </div>
       </div>  
       </div>
    design:
      columns: '1'

  - block: markdown
    id: experience
    content:
      title: '🌍 Experience'
      subtitle: ''
      text: |-
       <div class="experience-item">
        <div class="experience-image">
          <img src="/media/experience/sharpa.webp" alt="Sharpa">
        </div>
        <div class="experience-info">
         <div><strong>Sharpa Robotics</strong>, Tactile Department, Shanghai, China</div>
         <div><em>Research Intern</em></div>
        </div>  
        <div class="experience-date">
        Jun. 2026 -- Present
        </div>
       </div>


       <div class="experience-item">
        <div class="experience-image">
          <img src="/media/experience/nus.jpg" alt="nus">
        </div>
        <div class="experience-info">
         <div><strong>National University of Singapore</strong>, Sinapore</div>
         <div><em>Visiting Student</em></div>
        </div>  
        <div class="experience-date">
        Aug. 2023
        </div>
       </div>


       <div class="experience-item">
        <div class="experience-image">
          <img src="/media/experience/hku.png" alt="hku">
        </div>
        <div class="experience-info">
         <div><strong>The University of Hong Kong</strong>, Hong Kong, China</div>
         <div><em>Summer Research Programme</em></div>
        </div>  
        <div class="experience-date">
        Jun. 2021 -- Aug. 2021
        </div>
       </div>
       
      # <div class="experience-item">
      #  <div class="experience-image">
      #    <img src="/media/experience/sharpa.webp" alt="Sharpa">
      #  </div>
      #  <div class="experience-info">
      #   <div><strong>Deep robotics</strong>, Hangzhou, China</div>
      #   <div><em>Summer Research Intern</em></div>
      #  </div>  
      #  <div class="experience-date">
      #  Jun. 2023 -- Jul. 2023
      #  </div>
      # </div>
       
    design:
      columns: '1'


  - block: markdown
    id: service
    content:
      title: '😀 Service'
      subtitle: ''
      text: |-
        - **Reviewer**: RA-L (2025) 
        - **Teaching Assistant**: Engineering Materials, Zhejiang University, 2024 Fall
        - **President of the Graduate Student Association**, Department of Mechanical Engineering, Zhejiang University, 2024-2025
        - **Volunteer**: "Five-Star Volunteer" award, Zhejiang University, with over **400** cumulative volunteer hours
    design:
      columns: '1'

  
  - block: markdown
    id: others
    content:
      title: '🎀 Others'
      subtitle: ''
      text: |-
       Outside of research, I enjoy music, sports, photography, and traveling.
       - Piano & Vocal Music (both Amateur Grade 10 certified) 
       - Tennis & Fitness enthusiast
       - Beginner photographer :)
    design:
      columns: '1'




      #- block: collection
  #  id: honors
  #  content:
  #    title: Honors&Awards
  #    text: ''
  #    filters:
  #      folders:
  #        - publications
  #      exclude_featured: flase
  #  design:
  #    view: citation

  #- block: collection
  #  id: others
  #  content:
  #    title: Others
  #    filters:
  #      folders:
  #        - events
  #  design:
  #    view: card
  
---
