---
title: ''
summary: 'Portfólio de Ruan Andrew: desenvolvimento Backend com Java e Spring Boot, Machine Learning e Ciência de Dados.'
date: 2026-10-22
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: 'Olá, eu sou'
      show_status: true
      show_scroll_indicator: false
      typewriter:
        enable: true
        prefix: 'Trabalho com'
        strings:
          - 'Java e Spring Boot'
          - 'Machine Learning'
          - 'Ciência de Dados'
        type_speed: 60
        delete_speed: 35
        pause_time: 2200
      cta_buttons:
        - text: 'Conheça meus projetos'
          url: '#projects'
          icon: arrow-down
        - text: 'Entre em contato'
          url: '#contact'
          icon: envelope
    design:
      style: centered
      # avatar_shape: circle
      animations: true
      background:
        color:
          light: '#fafafa'
          dark: '#0a0a0f'
      spacing:
        padding: ['6rem', '0', '4rem', '0']

  - block: portfolio
    id: projects
    content:
      title: 'Projetos em destaque'
      subtitle: 'Desenvolvimento Backend, Machine Learning e Ciência de Dados'
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: 'Todos'
          tag: '*'
        - name: 'Backend'
          tag: 'Backend'
        - name: 'Machine Learning'
          tag: 'Machine Learning'
        - name: 'Ciência de Dados'
          tag: 'Ciência de Dados'
        - name: 'Pesquisa'
          tag: 'Pesquisa'
      default_button_index: 0
    design:
      columns: 3
      fallback_icon: code-bracket
      background:
        color:
          light: '#ffffff'
          dark: '#0d0d12'
      spacing:
        padding: ['4rem', '0', '4rem', '0']

  - block: tech-stack
    id: skills
    content:
      title: 'Tecnologias e ferramentas'
      subtitle: 'Tecnologias que utilizo em desenvolvimento de software, testes e ciência de dados'
      categories:
        - name: 'Linguagens'
          items:
            - name: 'Java'
              icon: devicon/java
            - name: 'Python'
              icon: devicon/python

        - name: 'Backend e APIs'
          items:
            - name: 'Spring Boot'
              icon: devicon/spring
            - name: 'Spring Security'
              icon: simple-icons/springsecurity

        - name: 'Banco de dados e persistência'
          items:
            - name: 'SQL'
              icon: devicon/postgresql
            - name: 'PostgreSQL'
              icon: devicon/postgresql
            - name: 'MySQL'
              icon: devicon/mysql
            - name: 'Flyway'
              icon: simple-icons/flyway

        - name: 'Testes e qualidade'
          items:
            - name: 'JUnit 5'
              icon: simple-icons/junit5
            - name: 'Testcontainers'
              icon: simple-icons/testcontainers
            - name: 'Mockito'
              icon: simple-icons/mockito

        - name: 'DevOps e ferramentas'
          items:
            - name: 'Maven'
              icon: devicon/maven
            - name: 'Docker'
              icon: devicon/docker
            - name: 'Docker Compose'
              icon: devicon/docker
            - name: 'Git'
              icon: devicon/git
            - name: 'GitHub Actions'
              icon: devicon/githubactions

        - name: 'Dados, Machine Learning e Cloud'
          items:
            - name: 'Pandas'
              icon: devicon/pandas
            - name: 'NumPy'
              icon: devicon/numpy
            - name: 'Scikit-learn'
              icon: devicon/scikitlearn
            - name: 'PyTorch'
              icon: devicon/pytorch
            - name: 'Matplotlib'
              icon: devicon/matplotlib
            - name: 'Jupyter Notebook'
              icon: devicon/jupyter
            - name: 'AWS'
              icon: devicon/amazonwebservices
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: '#f5f5f5'
          dark: '#08080c'
      spacing:
        padding: ['4rem', '0', '4rem', '0']
  
  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      date_format: 'Jan 2006'
      is_education_first: false
      background:
        color:
          light: '#ffffff'
          dark: '#0d0d12'
      spacing:
        padding: ['4rem', '0', '4rem', '0']

  - block: contact-info
    id: contact
    content:
      title: 'Vamos conversar?'
      subtitle: 'Oportunidades, colaboração e projetos de tecnologia'
      text: |
        Busco oportunidades como Desenvolvedor Backend Júnior e estágio em Ciência de Dados. Estou aberto a conversar sobre desenvolvimento de software, APIs, testes automatizados, dados e aprendizado de máquina.
      email: 'ruanandrew06@gmail.com'
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: '#ffffff'
          dark: '#0d0d12'
      spacing:
        padding: ['4rem', '0', '4rem', '0']

  - block: cta-card
    content:
      title: 'Aberto a oportunidades'
      text: |
        Confira meus repositórios para conhecer os projetos e acompanhar a evolução do meu trabalho.
      button:
        text: 'Acessar meu GitHub'
        url: 'https://github.com/RuanAndrew'
        new_tab: true
    design:
      card:
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
      text_color: dark
      background:
        color:
          light: '#f5f5f5'
          dark: '#08080c'
      spacing:
        padding: ['4rem', '0', '6rem', '0']
---