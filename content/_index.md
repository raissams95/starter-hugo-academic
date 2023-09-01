---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Post-doctoral researcher (ingenieure de Recherche) 
          company: Conservatoire National des Arts et Metiers
          company_url: 'https://www.cnam.fr'
          location: Paris, France
          date_start: '2021-12-01'
          date_end: ''
          description: Genomic and transcriptomic research on Chikungunya virus infection.
          Advisor: Dr. Jean-François Zagury
        - title: Professor of Oncotic Cytology
          company: Centro Universitário Metodista Izabela Hendrix
          company_url: 'http://izabelahendrix.edu.br'
          location: Belo Horizonte, Brazil
          date_start: '2018-08-01'
          date_end: '2018-12-31'
          description: Teaching Oncotic Cytology courses at the BSc in Biomedical Sciences and assessing students' activities and performance to record their academic progress.
        - title: Ph.D student in Genetics applied to Bioinformatic
          company: Universidade Federal de Minas Gerais
          company_url: 'http://ufmg.br'
          location: Belo Horizonte, Brazil
          date_start: '2018-08-01'
          date_end: '2021-11-30'
          description: Composition of Peruvian Loxosceles laeta venom revealed through NGS transcriptomic analysis and the development of the computational tool PepLess.
        - title: Monitoring in biochemistry and genetics courses
          company: Universidade Federal de Minas Gerais
          company_url: 'http://ufmg.br'
          location: Belo Horizonte, Brazil
          date_start: '2018-08-01'
          date_end: '2021-11-30'
          description: Responsible for certain courses in biochemistry and genetics (as a doctoral assistant) from the chair professor.
        - title: Higher Education Support Technician
          company: Universidade Federal de Minas Gerais
          company_url: 'https://ufmg.br'
          location: Belo Horizonte, Brazil
          date_start: '2017-01-01'
          date_end: '2017-12-31'
          description: Provide technical support and assistance to faculty and students in laboratory experiments and research projects.
        - title: Master's student in Bioinformatics
          company: Universidade Federal de Minas Gerais
          company_url: 'http://ufmg.br'
          location: Belo Horizonte, Brazil
          date_start: '2017-07-01'
          date_end: '2018-07-31'
          description: Metalloproteinases diversity in the venom gland of Peruvian spider Loxosceles laeta revealed by transcriptome analysis.
        - title: Monitoring in Cytology/General Histology and Special Histology courses
          company: Universidade Fumec
          company_url: 'https://www.fumec.br'
          location: Belo Horizonte, Brazil
          date_start: '2016-01-01'
          date_end: '2016-12-31'
          description: Assisting and conducting laboratory sessions and guiding students during practical exercises.
        - title: Bachelor of Science in Biomedical Sciences 
          company: Universidade Fumec
          company_url: 'https://www.fumec.br'
          location: Belo Horizonte, Brazil
          date_start: '2013-01-01'
          date_end: '2016-12-31'
          description: Specialization in clinical analysis and molecular biology and development of bioinformatics database for laboratory management.
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: raissa.medina-santos@lecnam.net
      phone: +33 01 40 27 21 37
      address:
        street: 2, rue Conté
        city: Paris
        region: 
        postcode: '75003'
        country: France
        country_code: FR
    design:
      columns: '2'
---
