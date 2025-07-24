---
title: Projects
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Project Portfolio
      subtitle: A showcase of my key technical projects and solutions
      text: |
        Here are some of the major projects I've worked on, demonstrating my expertise in cloud security, mobile development, and web applications.
      
      # Project configurations
      filters:
        folders:
          - project
      
      # Default portfolio settings
      default_button_index: 0
      
      # Custom project entries
      items:
        - name: "Accuknox Cloud Security Solution"
          description: "A comprehensive cloud security platform providing real-time threat detection, compliance monitoring, and vulnerability assessment for cloud infrastructure. Built with modern security frameworks and integrated with major cloud providers."
          tags: ["Cloud Security", "DevSecOps", "Monitoring", "Compliance"]
          
        - name: "ScreenPro"
          description: "A professional screen recording and video editing application designed for content creators and professionals. Features include multi-screen capture, real-time editing, and seamless export functionality with advanced compression algorithms."
          tags: ["Mobile Development", "Video Processing", "UI/UX", "Performance Optimization"]
          
        - name: "PhoneShop"
          description: "A full-featured e-commerce platform specializing in mobile devices and accessories. Includes user authentication, payment gateway integration, inventory management, and responsive design for optimal shopping experience across all devices."
          tags: ["E-commerce", "Web Development", "Payment Systems", "Responsive Design"]
    
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false
---
