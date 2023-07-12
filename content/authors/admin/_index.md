---
# Display name
title: Jialu Zhang 

# Full name (for SEO)
first_name: Jialu
last_name: Zhang

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: CS PhD Student 

# Organizations/Affiliations to show in About widget
organizations:
  - name: Yale University
    url: https://cpsc.yale.edu/

# Short bio (displayed in user profile at end of posts)
bio: My research interests lie in programming languages and software engineering. I focus on automatically preventing, detecting, and repairing crucial errors in programs across different fields such as systems, software engineering and CS education.

# Interests to show in About widget
interests:
  - LLM for Debugging
  - LLM for CS Education
  - AI-assisting Programming
  - Automated Program Repair

# Education to show in About widget
education:
  courses:
    - course: PhD in Computer Science
      institution: Yale University
      year: 2023 
    - course: BS in Electrical and Computer Engineering (IEEE Honor Class)
      institution: Shanghai Jiao Tong University
      year: 2017

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: '/#contact'
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/jialu-zhang-4ab17a126/

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.yaml`,
# and uncomment the lines below.
  - icon: cv
    icon_pack: ai
    link: uploads/resume.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: true
---


I am a researcher specializing in __Large Language Models (LLM) for Code__. I design the next-generation tool to help programmers better fight new emerging coding chanllenges in this AI Generated Code (AIGC) era. 

To enhance the productivity of programmers, we designed {{< staticref "uploads/ISSTA2022.pdf" "newtab" >}}Gmerge{{< /staticref >}}, the first tool that used GPT-3 to automatically resolve __300+__ real-world merge conflicts in Microsoft Edge. 

In support of CS Education, we developed {{< staticref "uploads/PyDex.pdf" "newtab" >}}Pydex{{< /staticref >}}. Powered by Codex, Pydex first gains the capability to repair both syntactic and semantic errors in students' Python programs, where existing tools were exclusively tailored to one type of these errors, but never both.

I took a stab at competitive programming, serving as the coach for the Yale ICPC Team. Research-wise, we  firstly introduced competitive programming to PL/SE community by presenting {{< staticref "uploads/ASE2022.pdf" "newtab" >}}Clef{{< /staticref >}}. Clef can repair very interesting competitive-level programs, including fixing non-functional property issues such as __time__ and __memory limit exceeded errors__.

I received my PhD at Yale University, advised by __Ruzica Piskac__. 
In the past two summers, I interned at Microsoft Research (MSR) on Large Language Models. I was mentored by __Shuvendu Lahiri__, __Sumit Gulwani__, and __Jose Cambronero__. We had a blast.