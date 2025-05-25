---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GLITCH: Automated Polyglot Security Smell Detection in Infrastructure as Code"
authors: [nuno-saavedra, jff]
date: 2022-07-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-01T22:42:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In *International Conference on Automated Software Engineering, 2022*"
publication_short: "In *ASE 2022*"
publication_ranking: "<b>CORE A* conference</b>"

# Awards
award_text: "**Awarded:** _Artifact Evaluation Award (Reusable)_"

abstract: "Infrastructure as Code (IaC) is the process of managing IT infrastructure via programmable configuration files (also called IaC scripts). Like other software artifacts, IaC scripts may contain security smells, which are coding patterns that can result in security weaknesses. Automated analysis tools to detect security smells in IaC scripts exist, but they focus on specific technologies such as Puppet, Ansible, or Chef. This means that when the detection of a new smell is implemented in one of the tools, it is not immediately available for the technologies supported by the other tools --- the only option is to duplicate the effort.


This paper presents an approach that enables consistent security smell detection across different IaC technologies. We conduct a large-scale empirical study that analyzes security smells on three large datasets containing 196,755 IaC scripts and 12,281,251 LOC. We show that all categories of security smells are identified across all datasets and we identify some smells that might affect many IaC projects. To conduct this study, we developed GLITCH, a new technology-agnostic framework that enables automated polyglot smell detection by transforming IaC scripts into an intermediate representation, on which different security smell detectors can be defined. GLITCH currently supports the detection of nine different security smells in scripts written in Ansible, Chef, or Puppet. We compare GLITCH with state-of-the-art security smell detectors. The results obtained not only show that GLITCH can reduce the effort of writing security smell analyses for multiple IaC technologies, but also that it has higher precision and recall than the current state-of-the-art tools."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: publication/2022/ASE/ase22-glitch.pdf
url_code: 
url_dataset: https://doi.org/10.6084/m9.figshare.19726603.v2
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: ["smartbugs"]
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

aliases:
    - /publications/2022/ASE

---


---
