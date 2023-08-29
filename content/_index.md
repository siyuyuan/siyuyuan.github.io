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
  - block: markdown
    id: news
    content:
      title: News
      text: 
        + ***July*** **2023**\:Our paper [Coscript](https://siyuyuan.github.io/publication/distilling-script-knowledge-from-large-language-models-for-constrained-language-planning/) got an <font color="red">**Outstanding Paper Award**</font> in ACL 2023 (top 1%)!

        + ***July*** **2023**\:Gave a talk for Peking University Shenzhen Graduate School Shanghai Alumni Association.

        + ***May*** **2023**\:Check out two pre-prints on Analogical Reasoning. [AnalogyKB](https://siyuyuan.github.io/publication/analogykb-unlocking-analogical-reasoning-of-language-models-with-a-million-scale-knowledge-base/) is a million-scale analogy KB derived from existing KGs, to enable machines to achieve analogical reasoning skills. [SCAR](https://siyuyuan.github.io/publication/beneath-surface-similarity-large-language-models-make-reasonable-scientific-analogies-after-structure-abduction/) is a new challenge for evaluating the structure abduction ability of LLMs for scientific analogies, which is essential for human-like analogical reasoning.
      
        + ***May*** **2023**\:Two papers accepted to ACL 2023! One is [Coscript](https://siyuyuan.github.io/publication/distilling-script-knowledge-from-large-language-models-for-constrained-language-planning/) on constraint language planning, and the other is [KPCE](https://siyuyuan.github.io/publication/causality-aware-concept-extraction-based-on-knowledge-guided-prompting/) on concept extraction through the lens of a Structural Causal Model.  
        
        + ***Oct.*** **2022**\:Our work [Generative Entity Typing with Curriculum Learning](https://siyuyuan.github.io/publication/generative-entity-typing-with-curriculum-learning/) got accepted at EMNLP 2022!
        
        + ***Sept.*** **2022**\:Our work ([CISPE](https://arxiv.org/pdf/2207.13254.pdf)) about emotion recognition in conversation has been reported in the ECML PKDD 2022 online!
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
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
        - title: Research Intern
          company: Microsoft Research Lab Asia
          company_url: ''
          company_logo: org-Microsoft
          location: Shanghai, China
          date_start: '2023-09-04'
          date_end: ''
          description: Mentored by [Dr. Kaitao Song](https://www.microsoft.com/en-us/research/people/kaitaosong/) and [Dr. Kan Ren](https://www.microsoft.com/en-us/research/people/kanren/). Autonomous Agents with Planning and Tool Use.
        - title: Research Intern
          company: ByteDance AI Lab
          company_url: ''
          company_logo: org-ByteDance
          location: Shanghai, China
          date_start: '2023-01-01'
          date_end: '2023-05-31'
          description: Mentored by [Dr. Jiaze Chen](https://scholar.google.com/citations?user=Vt1j3kEAAAAJ&hl=zh-CN) and [Dr. Changzhi Sun](https://www.czsun.site/). Working on LLM Evaluation and Instruction Tuning on LLMs.
        - title: Research Intern
          company: Brain Technologies Inc
          company_url: ''
          company_logo: org-brain
          location: Remote
          date_start: '2022-06-01'
          date_end: '2022-09-30'
          description: Mentored by [Dr. Charles Jankowski](https://www.linkedin.com/in/charlesjankowski). Working on Symbolic Knowledge Distillation and LLM Prompt Engineering.
        - title: Student Researcher
          company: Knowledge Works Lab at Fudan University
          company_url: ''
          company_logo: org-KW
          location: Shanghai, China
          date_start: '2019-07-01'
          date_end: ''
          description: Working on Knowledge Generation and Knowledge Graph.
    design:
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-07-14'
          description: ''
          organization: Association for Computational Linguistics
          organization_url: ''
          title: ACL 2023 Outstanding Paper Award
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-06-30'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Graduate Student of Shanghai Colleges and University
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-12-01'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Student Pacemaker of Fudan University
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2018-10-01'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: China National Scholarship
          url: ''
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
---
