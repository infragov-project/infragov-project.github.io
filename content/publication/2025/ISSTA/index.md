---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "InfraFix: Technology-Agnostic Repair of Infrastructure as Code"
authors: [nuno-saavedra, jff, alexandra-mendes]
date: 2025-04-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-04-11T22:42:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*International Symposium on Software Testing and Analysis (ISSTA), 2025, Tool Demonstrations Track*"
publication_short: "In *ISSTA 2025, Tool Demonstrations Track*"

publication_ranking: "<b>CORE A conference</b>"

abstract: "Infrastructure as Code (IaC) enables scalable and automated IT infrastructure management but is prone to errors that can lead to security vulnerabilities, outages, and data loss. While prior research has focused on detecting IaC issues, Automated Program Repair (APR) remains underexplored, largely due to the lack of suitable specifications.


In this work, we propose InfraFix, the first technology-agnostic framework for repairing IaC scripts. Unlike prior approaches, InfraFix allows APR techniques to be guided by diverse information sources. Additionally, we introduce a novel approach for generating repair scenarios, enabling large-scale evaluation of APR techniques for IaC. We implement and evaluate InfraFix using an SMT-based repair module and a state inference module that uses system calls, demonstrating its effectiveness across 254,755 repair scenarios with a success rate of 95.5%. 


Our work provides a foundation for advancing APR in IaC by enabling researchers to experiment with new state inference and repair techniques using InfraFix and to evaluate their approaches at scale with our repair scenario generation method."
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

url_pdf: https://arxiv.org/pdf/2503.17220
url_code: https://github.com/sr-lab/GLITCH/tree/interactive_repair
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=ETSW0n9DcdU

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
projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

aliases:
    - /publications/2025/ISSTA-InfraFix

# Awards
award_text: "**Awarded:** Artifact Evaluation Award (Reusable)"
---


---
