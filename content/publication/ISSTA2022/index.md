---
title: 'Using pre-trained language models to resolve textual and semantic merge conflicts (experience paper)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Todd Mytkowicz
  - Mike Kaufman
  - Ruzica Piskac
  - Shuvendu K. Lahiri

# Author notes (optional)


date: '2022-07-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ISSTA2022*
publication_short: In *ISSTA2022*

abstract: Program merging is standard practice when developers integrate their individual changes to a common code base. When the merge algorithm fails, this is called a merge conflict. The conflict either manifests as a textual merge conflict where the merge fails to pro- duce code, or as a semantic merge conflict where the merged code results in compiler errors or broken tests. Resolving these conflicts for large code projects is expensive because it requires developers to manually identify the sources of conflicts and correct them. In this paper, we explore the feasibility of automatically repairing merge conflicts (both textual and semantic) using k-shot learning with pre-trained large neural language models (LM) such as GPT-3. One of the challenges in leveraging such language models is fitting the examples and the queries within a small prompt (2048 tokens). We evaluate LMs and k-shot learning for both textual and semantic merge conflicts for Microsoft Edge. Our results are mixed. On one-hand, LMs provide the state-of-the-art (SOTA) performance on semantic merge conflict resolution for Edge compared to earlier symbolic approaches; on the other hand, LMs do not yet obviate the benefits of special purpose domain-specific languages (DSL) for restricted patterns for program synthesis.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.microsoft.com/en-us/research/uploads/prod/2022/07/issta22-merge-conflicts-llm.pdf'
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
  caption: 'A Semantics Conflict'
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
