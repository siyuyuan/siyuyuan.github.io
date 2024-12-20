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
        + ***Dec.*** **2024** I got the <font color="red">**China National Scholarship for Doctoral Students**</font>!

        + ***Sep.*** **2024** Our survey about [Role-Playing Agents](https://siyuyuan.github.io/publication/from-persona-to-personalization-a-survey-on-role-playing-language-agents/) is accepted to TMLR!

        + ***Sep.*** **2024** Three papers accepted to EMNLP 2024 Main Conference! One is about [character profiling](https://siyuyuan.github.io/publication/evaluating-character-understanding-of-large-language-models-via-character-profiling-from-fictional-works/), one is about [pun understanding](https://siyuyuan.github.io/publication/a-good-pun-is-its-own-reword-can-large-language-models-understand-puns/) and one is about [concept understanding with analogy](https://siyuyuan.github.io/publication/boosting-scientific-concepts-understanding-can-analogy-from-teacher-models-empower-student-models/).

        + ***Jun.*** **2024** How to automatically extend the specialized agent to multi-agent systems to improve task-solving capability? We propose [EvoAgent](https://siyuyuan.github.io/publication/evoagent-towards-automatic-multi-agent-generation-via-evolutionary-algorithms/), a generic method to automatically extend expert agents to multi-agent systems via the evolutionary algorithm. EvoAgent can be generalized to any LLM-based agent framework, and significantly enhance the task-solving capabilities of LLM-based agents!!

        + ***Jun.*** **2024** How can we enable autonomous language agents to consistently achieve high-level goals without training? Try [SelfGoal](https://siyuyuan.github.io/publication/selfgoal-your-language-agents-already-know-how-to-achieve-high-level-goals/), a novel automatic approach designed to enhance agents’ capabilities to achieve high-level goals with limited human prior and environmental feedback.
    
        + ***May.*** **2024** Congratulations on [AnalogyKB](https://siyuyuan.github.io/publication/analogykb-unlocking-analogical-reasoning-of-language-models-with-a-million-scale-knowledge-base/), [TimeArena](https://siyuyuan.github.io/publication/incharacter-evaluating-personality-fidelity-in-role-playing-agents-through-psychological-interviews/) and [InCharacter](https://siyuyuan.github.io/publication/incharacter-evaluating-personality-fidelity-in-role-playing-agents-through-psychological-interviews/) being accepted to ACL 2024 Main Conference and one paper being accepted to ACL 2024 Findings! See you in Bangkok, Thailand!

        + ***Apr.*** **2024** Explore the [First Survey on Role-Playing Agents](https://siyuyuan.github.io/publication/from-persona-to-personalization-a-survey-on-role-playing-language-agents/)! Discover insights into RPLA technologies, applications, and the potential for human-AI coexistence. 
    
        + ***Apr.*** **2024** Can large language models understand puns? Check out our new [pre-prints](https://siyuyuan.github.io/publication/a-good-pun-is-its-own-reword-can-large-language-models-understand-puns/). We leverage three popular pun tasks to systematically evaluate LLMs’ capability of understanding puns.
    
        + ***Apr.*** **2024** Check out two pre-prints on Role-playing Agents, which extend [InCharacter](https://siyuyuan.github.io/publication/incharacter-evaluating-personality-fidelity-in-role-playing-agents-through-psychological-interviews/)! [CROSS](https://siyuyuan.github.io/publication/evaluating-character-understanding-of-large-language-models-via-character-profiling-from-fictional-works/) systematically evaluate LLMs’ capability on the character profiling task, i.e., summarizing profiles for characters from fictional works. [LIFECHOICE](https://siyuyuan.github.io/publication/character-is-destiny-can-large-language-models-simulate-persona-driven-decisions-in-role-playing/) investigate whether LLMs can predict characters’ decisions provided with the preceding stories in high-quality novels. 
    
        + ***Feb.*** **2024** Congratulations on [EasyTool](https://siyuyuan.github.io/publication/easytool-enhancing-llm-based-agents-with-concise-tool-instruction/) and [TaskBench](https://arxiv.org/abs/2311.18760) being accepted to [ICLR 2024 Workshop on LLM Agents](https://llmagents.github.io/)!
    
        + ***Feb.*** **2024** Introducing [TimeArena](https://siyuyuan.github.io/publication/incharacter-evaluating-personality-fidelity-in-role-playing-agents-through-psychological-interviews/), a Time-Aware simulated textual environment for language agents to complete multiple tasks in the *shortest time*, which means simulating realistic temporal & resource constraints! Check out our [project page](https://time-arena.github.io/) for more details!
    
        + ***Feb.*** **2024** [InCharacter](https://siyuyuan.github.io/publication/incharacter-evaluating-personality-fidelity-in-role-playing-agents-through-psychological-interviews/) is out! A new method to test personality fidelity in Role-Playing Agents using psychological interviews. Play with InCharacter [demo](https://incharacter.theirstory.cn/)!
    
        + ***Jan.*** **2024** Enhance LLM-based agents with [EasyTool](https://siyuyuan.github.io/publication/easytool-enhancing-llm-based-agents-with-concise-tool-instruction/)! Effortlessly convert complex, varied tool documentation into streamlined, unified tool instructions. Significantly improve performance and reduce token consumption!
    
        + ***Dec.*** **2023** Gave a talk at [Tencent AI Lab](https://ai.tencent.com/ailab/en/index/) about [Coscript](https://siyuyuan.github.io/publication/distilling-script-knowledge-from-large-language-models-for-constrained-language-planning/). Thanks for the invitation!
    
        + ***Dec.*** **2023** Congratulations on our paper [IdiomKB](https://siyuyuan.github.io/publication/translate-meanings-not-just-words-idiomkb-role-in-optimizing-idiomatic-translation-with-language-models/) being accepted to AAAI 2024! Our work focuses on creating a multilingual knowledge base for idioms with the help of Large Language Models (LLMs), aiming to improve idiomatic translation in smaller models.
    
        + ***Dec.*** **2023** Join in EMNLP 2023, Singapore! Our work [SCAR](https://siyuyuan.github.io/publication/beneath-surface-similarity-large-language-models-make-reasonable-scientific-analogies-after-structure-abduction/) will be in the poster session!

        + ***Nov.*** **2023** We released [TaskBench](https://arxiv.org/abs/2311.18760), a benchmark for evaluating the task automation capabilities of large language models.
    
        + ***Oct.*** **2023** Check out our [Auction Arena](https://arxiv.org/abs/2310.05746)! We explore how LLMs navigate the complex and dynamic environment of auctions! We introduce AucArena, a novel simulation environment to evaluate the planning and strategic abilities of LLMs. Play with [arena demo](https://auction-arena.github.io/) and see if you can beat AI!
    
        + ***Oct.*** **2023** Our paper [SCAR](https://siyuyuan.github.io/publication/beneath-surface-similarity-large-language-models-make-reasonable-scientific-analogies-after-structure-abduction/) on analogical reasoning got accepted at EMNLP 2023 (Findings)! See you in Singapore.
    
        + ***Sept.*** **2023** Start Student Researcher Internship at [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), advised by [Dr. Kaitao Song](https://www.microsoft.com/en-us/research/people/kaitaosong/)!

        + ***July*** **2023** Our paper [Coscript](https://siyuyuan.github.io/publication/distilling-script-knowledge-from-large-language-models-for-constrained-language-planning/) got an <font color="red">**Outstanding Paper Award**</font> in ACL 2023 (top 1%)!
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
          date_end: '2024-06-30'
          description: Mentored by [Dr. Kaitao Song](https://www.microsoft.com/en-us/research/people/kaitaosong/) and [Dr. Kan Ren](https://www.microsoft.com/en-us/research/people/kanren/). Autonomous Agents with Planning and Tool Use.
        - title: Research Intern
          company: ByteDance AI Lab
          company_url: ''
          company_logo: org-ByteDance
          location: Shanghai, China
          date_start: '2023-01-01'
          date_end: '2023-05-31'
          description: Mentored by [Jiaze Chen](https://scholar.google.com/citations?user=Vt1j3kEAAAAJ&hl=zh-CN) and [Dr. Changzhi Sun](https://www.czsun.site/). Working on LLM Evaluation and Instruction Tuning on LLMs.
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
          date_start: '2024-12-01'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: China National Scholarship for Doctoral Students
          url: ''
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
          date_start: '2018-12-01'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: China National Scholarship for Undergraduate Students
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
