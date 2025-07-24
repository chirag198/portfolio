---
title: "Chirag Aggarwal"
date: 2022-10-24
type: landing

sections:
  # Hero Section with Introduction
  - block: hero
    demo: true
    content:
      title: "Welcome to My Portfolio"
      image:
        filename: hero-academic.png
      cta:
        url: "./resume.md"
        label: "View My Resume"
        icon_pack: fas
        icon: download
      cta_alt:
        url: "./projects.md"
        label: "Explore Projects"
      cta_note:
        label: "Available for collaboration and opportunities"
      text: |
        **Software Engineer | Full-Stack Developer | Problem Solver**
        
        Welcome! I'm Chirag Aggarwal, a passionate software engineer with expertise in full-stack development, system design, and modern web technologies. I build scalable applications and love solving complex technical challenges.
        
        Currently pursuing my Master's in Computer Science while working on innovative projects that blend cutting-edge technology with practical solutions.
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true

  # Navigation Quick Links
  - block: features
    content:
      title: "Quick Navigation"
      subtitle: "Explore different sections of my portfolio"
      items:
        - name: "💼 Experience"
          description: "Professional journey and work history"
          icon: briefcase
          icon_pack: fas
          url: "./experience.md"
        - name: "🎓 Education"
          description: "Academic background and achievements"
          icon: graduation-cap
          icon_pack: fas
          url: "./education.md"
        - name: "🚀 Projects"
          description: "Technical projects and innovations"
          icon: rocket
          icon_pack: fas
          url: "./projects.md"
        - name: "📄 Resume"
          description: "Complete professional summary"
          icon: file-alt
          icon_pack: fas
          url: "./resume.md"

  # Personal Statement Section
  - block: markdown
    content:
      title: "About Me"
      subtitle: "My Journey & Passion"
      text: |
        ## Who I Am
        
        I'm a dedicated software engineer with a strong foundation in computer science and a passion for creating impactful technology solutions. My journey in software development has been driven by curiosity, continuous learning, and the desire to build applications that make a difference.
        
        ## What I Do
        
        - **Full-Stack Development**: Building end-to-end web applications using modern frameworks and technologies
        - **System Design**: Architecting scalable and efficient software systems
        - **Problem Solving**: Tackling complex technical challenges with analytical thinking
        - **Continuous Learning**: Staying updated with the latest technologies and best practices
        
        ## My Approach
        
        I believe in writing clean, maintainable code and following best practices in software development. I'm passionate about user experience, performance optimization, and building solutions that are both technically sound and user-friendly.
        
        ## Let's Connect
        
        I'm always interested in discussing new opportunities, collaborating on interesting projects, or simply connecting with fellow developers. Feel free to reach out!
    design:
      columns: '1'
      background:
        color: 'navy'
        text_color_light: true

  # Featured Projects Preview
  - block: portfolio
    id: projects
    content:
      title: "Featured Projects"
      subtitle: "Some of my recent work"
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Web Development
          tag: Web
        - name: Mobile
          tag: Mobile
        - name: AI/ML
          tag: AI
    design:
      columns: '2'
      view: showcase
      flip_alt_rows: false

  # Skills & Technologies
  - block: markdown
    content:
      title: "🛠️ Technical Skills"
      text: |
        ### Programming Languages
        **Python** • **JavaScript/TypeScript** • **Java** • **C++** • **Go** • **SQL**
        
        ### Frontend Technologies
        **React.js** • **Next.js** • **Vue.js** • **HTML5/CSS3** • **Tailwind CSS** • **Bootstrap**
        
        ### Backend Technologies
        **Node.js** • **Express.js** • **Django** • **Flask** • **Spring Boot** • **RESTful APIs**
        
        ### Databases & Cloud
        **MongoDB** • **PostgreSQL** • **MySQL** • **Redis** • **AWS** • **Google Cloud** • **Docker**
        
        ### Tools & Platforms
        **Git/GitHub** • **VS Code** • **Linux** • **CI/CD** • **Agile/Scrum** • **Testing Frameworks**
    design:
      columns: '1'
      background:
        color: '#f8f9fa'

  # Contact Call-to-Action
  - block: cta
    demo: true
    content:
      title: "Ready to Collaborate?"
      text: "I'm always open to discussing new opportunities, interesting projects, or potential collaborations. Let's build something amazing together!"
      cta:
        url: "mailto:your-email@example.com"
        label: "Get In Touch"
        icon_pack: fas
        icon: envelope
      cta_alt:
        url: "./resume.md"
        label: "Download Resume"
        icon_pack: fas
        icon: download
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
---
