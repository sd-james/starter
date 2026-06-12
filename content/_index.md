---
title: Steven James – AI Researcher at the University of the Witwatersrand
summary: "Academic personal website for Steven James, AI researcher focusing on reinforcement learning and compositionality"
date: 2026-06-12
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        eyebrow: AI Researcher
        title: Steven James
        text: "AI researcher working on reinforcement learning, planning, and reusable abstractions"
        primary_action:
          text: Read my research
          url: /research/
          icon: hero/book-open
          style: gradient
        secondary_action:
          text: View publications
          url: /publications/
          icon: hero/newspaper
          style: text
        media:
          type: image
          src: assets/media/steven-james-portrait.jpg
          alt: Portrait of Steven James
    design:
        background:
          color:
            light: "#FAF9F6"
            dark: "#0B1021"
          gradient:
            type: radial
            start: "#3B4A85"
            end: transparent
            position: center
            shape: ellipse
            size: "80% 80%"
        layout: split-left
        size: viewport
        section_break:
          fade_bottom: "#FAF9F6"
    id: intro
  - block: features
    content:
        title: What I work on
        items:
          - name: Reinforcement learning and planning
            description: Developing algorithms for intelligent decision-making in complex environments.
            icon: hero/academic-cap
          - name: Abstractions and compositionality
            description: Studying reusable knowledge structures and their role in AI generalization.
            icon: hero/cube-transparent
          - name: Transfer and lifelong learning
            description: Enabling agents to adapt and learn across tasks and domains.
            icon: hero/arrow-path
          - name: Games as AI testbeds
            description: Using game environments to evaluate AI agents in challenging scenarios.
            icon: hero/gamepad
    design:
        background:
          color:
            light: "#FAF9F6"
            dark: "#0B1021"
        layout: grid
        section_break:
          fade_top: "#FAF9F6"
          fade_bottom: "#FAF9F6"
    id: work-on
  - block: collection
    content:
        title: Featured Research
        summary: Highlighted publications and projects.
        collection: publication
        filter: "featured: true"
        limit: 3
        show_counts: true
        show_categories: true
    design:
        background:
          color:
            light: "#FFFFFF"
            dark: "#121212"
        section_break:
          fade_top: "#FAF9F6"
    id: featured-research
  - block: cta-card
    content:
        title: Speaking Engagements
        text: "I give talks and workshops on reinforcement learning, AI agents, planning, and AI system capabilities."
        button:
          text: Invite me to speak
          url: "/contact/#speaking"
          icon: hero/megaphone
    design:
        background:
          color:
            light: "#FAF9F6"
            dark: "#0B1021"
        card:
          css_class: glassmorphism-primary
          text_color: auto
          overlay_opacity: 0.15
    id: speaking
  - block: markdown
    content:
        title: Latest News
        markdown:
          |
            - **June 2026:** Presented a keynote on reinforcement learning at AI Summit 2026.
            - **May 2026:** Published a paper on abstraction learning in AI agents.
            - **April 2026:** Invited panelist at the International Planning Symposium.
            - **March 2026:** Released open-source code for transfer learning environments.
    design:
        section_break:
          fade_top: "#FAF9F6"
          fade_bottom: "#FAF9F6"
    id: news
  - block: cta-card
    content:
        title: Get in Touch
        text: "Feel free to reach out for collaboration, speaking engagements, or student supervision."
        button:
          text: Contact me
          url: /contact
          icon: hero/envelope
    design:
        background:
          color:
            light: "#FFFFFF"
            dark: "#121212"
        card:
          css_class: glassmorphism-primary
          text_color: auto
          overlay_opacity: 0.15
    id: contact
---
