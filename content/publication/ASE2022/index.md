---
title: 'Automated Feedback Generation for Competition-Level Code'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - De Li
  - John C. Kolesar
  - Hanyuan Shi
  - Ruzica Piskac

# Author notes (optional)


date: '2022-10-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ASE2022*
publication_short: In *ASE2022*

abstract: Competitive programming has become a popular way for programmers to test their skills. Competition-level programming problems are challenging in nature, and participants often fail to solve the problem on their first attempt. Some online platforms for competi-tive programming allow programmers to practice on competitionlevel problems, and the standard feedback for an incorrect practice submission is the first test case that the submission fails. Often, the failed test case does not provide programmers with enough information to resolve the errors in their code, and they abandon the problem after making several more unsuccessful attempts. We present Clef, the first data-driven tool that can generate feedback on competition-level code automatically by repairing programmers’ incorrect submissions. The key development is that Clef can learn how to generate repairs for incorrect submissions by examining the repairs that other programmers made to their own submissions over time. Since the differences between an incorrect program and a correct program for the same task may be significant, we introduce a new data structure, merge trees, to capture the changes between submissions. Merge trees are versatile: they can encode both large algorithm-level redesigns and small statement-level alterations. We evaluated Clef on six real-world problems from Codeforces, the world’s largest platform for competitive programming. Clef achieves 41.8% accuracy in repairing programmers’ incorrect submissions. When given incorrect submissions from programmers who never found the solution to a problem on their own, Clef repairs the users’ programs 34.1% of the time.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2206.01848.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'ConfigX Overview'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
