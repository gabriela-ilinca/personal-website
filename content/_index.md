---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
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
        - title: Undergraduate Researcher
          company: Emory University Department of Economics
          company_url: ''
          company_logo: emory
          location: Atlanta
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
            Work with researchers at the Bank of Canada in a project using the Bank’s proprietary yearly Bitcoin Omnibus Survey to investigate cryptocurrency ownership. Present weekly on research progress and findings to SURE mentor and project stakeholders.
        - title: Software Engineer Intern
          company: Rainforest
          company_url: ''
          company_logo: rain
          location: Atlanta
          date_start: '2022-05-01'
          date_end: '2022-08-30'
          description: |2-
            Joined a startup fintech company to develop technology for independent software vendors (ISVs) to embed payments into their product. Used Go, Python, and Vue JS to specifically collect pertinent information and details from customers using Rainforest technology and storing them in an accessible database.      
        - title: Research Intern
          company: Georgia Tech Research Institute
          company_url: ''
          company_logo: gt
          location: Atlanta
          date_start: '2022-05-01'
          date_end: '2022-08-30'
          description: |2-
            Assisted in developing an Artificial Intelligence system that proactively initiates speech to support elderly people who live alone  
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/cadc9214519905881ba56b7bb0131beec4162fbf?raw=1
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          organization: DataCamp
          organization_url: datacamp.com
          title: Intermediate Regression with statsmodels in Python
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/823374d24fb62e8bb7e48d9ffc629d0925d0575f?raw=1
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          organization: DataCamp
          organization_url: datacamp.com
          title: Dimensionality Reduction in Python
          url: ''
        - certificate_url: https://www.linkedin.com/learning/certificates/6d35eb5e647cb53a8e1d927a6baaa61374f0d42e7470a0979d4456aea07421b1?u=2149178
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          organization: LinkedIn
          organization_url: linkedin.com
          title: Advanced and Specialized Statistics in Stata
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

---