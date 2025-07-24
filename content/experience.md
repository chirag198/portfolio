---
title: 'Experience'
date: 2023-10-24
type: landing
design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  # Work Experience Section
  - block: resume-experience
    content:
      title: 'Work Experience'
      username: admin
      # Experience entries
      experience:
        - title: 'Software Engineer'
          company: 'Technology Company'
          company_url: ''
          company_logo: ''
          location: 'Remote'
          date_start: '2022-01-01'
          date_end: ''
          description: |
            * Developed and maintained full-stack web applications using modern frameworks
            * Collaborated with cross-functional teams to deliver high-quality software solutions
            * Implemented responsive user interfaces and optimized application performance
            * Participated in code reviews and maintained coding standards
            * Worked with databases to design efficient data models and queries
            * Technologies Used: React.js, Node.js, Python, AWS, PostgreSQL

        - title: 'Junior Software Developer'
          company: 'Previous Technology Company'
          company_url: ''
          company_logo: ''
          location: 'Hybrid'
          date_start: '2021-06-01'
          date_end: '2021-12-31'
          description: |
            * Assisted in developing web applications using JavaScript and Python
            * Learned modern development frameworks and best practices
            * Participated in agile development processes and team collaborations
            * Gained experience in database design and API integration
            * Contributed to code documentation and testing procedures

        - title: 'Software Development Intern'
          company: 'Tech Startup'
          company_url: ''
          company_logo: ''
          location: 'On-site'
          date_start: '2020-06-01'
          date_end: '2020-08-31'
          description: |
            * Worked on frontend development using HTML, CSS, and JavaScript
            * Learned version control systems (Git) and collaborative development
            * Assisted in testing and debugging software applications
            * Gained exposure to software development lifecycle and project management
            * Developed problem-solving skills in a professional environment

    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  # Skills Section
  - block: resume-skills
    content:
      title: 'Technical Skills'
      username: admin
      skills:
        - name: 'Programming Languages'
          items:
            - 'JavaScript/TypeScript'
            - 'Python'
            - 'Java'
            - 'HTML5/CSS3'
            - 'SQL'
        - name: 'Frameworks & Technologies'
          items:
            - 'React.js'
            - 'Node.js'
            - 'Express.js'
            - 'Django'
            - 'Flask'
        - name: 'Tools & Platforms'
          items:
            - 'AWS'
            - 'Docker'
            - 'Git'
            - 'PostgreSQL'
            - 'MongoDB'
    design:
      show_skill_percentage: false

  # Awards Section
  - block: resume-awards
    content:
      title: 'Achievements & Certifications'
      username: admin
      awards:
        - title: 'AWS Cloud Practitioner Certification'
          date: '2023'
          awarder: 'Amazon Web Services'
          summary: 'Demonstrated foundational knowledge of AWS cloud services and best practices'
        - title: 'Best Team Player Award'
          date: '2022'
          awarder: 'Current Company'
          summary: 'Recognition for outstanding collaboration and teamwork in software development projects'

  # Languages Section
  - block: resume-languages
    content:
      title: 'Languages'
      username: admin
      languages:
        - name: 'English'
          proficiency: 'Fluent'
        - name: 'Hindi'
          proficiency: 'Native'
        - name: 'Punjabi'
          proficiency: 'Conversational'
---
